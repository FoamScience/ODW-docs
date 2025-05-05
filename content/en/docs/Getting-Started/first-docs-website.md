---
title: Your first website
description: A fast-paced guide to build your first documentation website with ODW
categories:
    - Examples
tags:
    - docs
weight: 3
---

## Perquisites

In principle, we need:
- An OpenFOAM installation
- [UV](https://github.com/astral-sh/uv) to manage the Python dependencies
- [Golang](https://go.dev/) and [Hugo](https://gohugo.io/) latest **extended** version.

You can check the exact requirements in this [apptainer definition file](https://github.com/FoamScience/ODW/blob/main/apptainer/odw.def). Alternatively you can create a container out of that definition with the help of the [OpenFOAM Apptainer Packaging mechanism](https://github.com/FoamScience/openfoam-apptainer-packaging).

## Create a new website

You can create an empty website with:
```bash
hugo new site my-docs
```

Since ODW is a hugo module, you can attach it to your website with:
```bash
cd my-docs
# Initialize your website as a module, username and repo name can be arbitrary
hugo mod init github.com/me/my-docs
# Link to ODW module
hugo mod get github.com/FoamScience/ODW
```

Make sure your docs are git-tracked:
```bash
cd my-docs
git init
```

That's all that needs to be done, really. To view your website:
```bash
cd my-docs
hugo server
# Then visit localhost:1313 in a browser
```

## Site configuration

We recommend copying this [website's configuration](https://github.com/FoamScience/ODW-docs/blob/main/hugo.toml) and put in your `hugo.toml`, at least as a starting point. The important bits are:
```toml
[taxonomies]
tag = "tags"
category = "categories"
contributor = "contributors"
api_tag = "api_tags"
api_namespaces = "api_namespaces"
adr_tag = "adr_tags"

[params.taxonomy]
taxonomyCloud = ["tags", "categories", "contributors", "api_tags", "api_namespaces", "adr_tags"]
taxonomyCloudTitle = ["Tag Cloud", "Categories", "Contributors", "API Tags", "API Namespaces", "ADR Tags"]
taxonomyPageHeader = ["tags", "categories", "contributors", "api_tags", "api_namespaces", "adr_tags"]

[markup]
  [markup.goldmark]
    [markup.goldmark.parser.attribute]
      block = true
    [markup.goldmark.renderer]
      unsafe = true
      hardWraps = true
      xhtml = true
    [markup.goldmark.renderHooks.link]
      enableDefault = false
  [markup.highlight]
    # See a complete list of available styles at https://xyproto.github.io/splash/docs/all.html
    style = "catppuccin-mocha"

[module]
  [module.hugoVersion]
    extended = true
    min = "0.140.0"
  [[module.imports]]
    path = "github.com/FoamScience/ODW"
    disable = false

```

You can also change the styling by adding a `assets/scss/_variables_project.scss`. Take a look at [our variables SCSS file](https://github.com/FoamScience/ODW/blob/main/assets/scss/_variables_project.scss) for ideas.

## Populate the website with content

Add content as you please (Hugo rules apply, and [Docsy](https://www.docsy.dev/docs/adding-content/) short-codes are available), but we recommend at least:
```bash
content/
  en/
    _index.md                       # landing page
    about/_index.md                 # An "about" page
    api/_index.md                   # API documentation
    ards/_index.md                  # ADRs
    blog/_index.md                  # The blog section
    docs/_index.md                  # Getting started, FAQ and tutorial pages
    tests/_index.md                 # Unit tests (if you like)
```

Each of these sections are optional, and you are free to structure the content however you see fit.

### Setup the landing page

The landing (home) page is setup through [`content/en/_index.md`](https://github.com/FoamScience/ODW-docs/blob/main/content/en/_index.md). This example landing page uses Docsy's cover and section short-codes which render like [this](/)

### Tutorials-style documentation

The frontmatter for the `docs` section is solely based on what Docsy and Hugo support. A minimal set of entries describes:
```yaml
---
title: Your first website
description: A fast-paced guide to build your first documentation website with ODW
categories:
    - Examples
tags:
    - docs
weight: 4 # This weight will control the ordering of pages on the sidebar
---
```

To make sure this section shows up in the top (main) menu, add a `content/en/docs/_index.md` with the following frontmatter:
```yaml
---
title: Documentation
linkTitle: Docs
menu:    # Add this to the main menu
  main:
    weight: 20
weight: 1
---
```

### API and unit test documentation

To generate the API and, optionally, the unit tests documentation, we need to use a ODW's CLI.

Get the CLI utility from your live site!
```bash
# In one terminal
cd my-docs
hugo serve # keep this running

# In another terminal
curl -O http://localhost:1313/scripts/odw
chmod +x ./odw
./odw --help
```

You can then generate the docs:
```bash
cd my-docs
openfoam2406 # Or source any other OpenFOAM environment
# DOC_DIR points to the root folder of the hugo website
# CODE_SRC_DIR points to the src folder where your libraries reside
# /tmp/foamcd.dbs is where the SQLITE databases are saved;
#                 if you keep this between runs, they are used as a "cache"
DOCS_DIR=$PWD CODE_SRC_DIR=<your/code/repo/folder> \
    ./odw docs /tmp/foamcd.dbs

# If you want to produce UT reports and link them to API classes:
# Setting CODE_TEST_DIR will turn on unit test processing and parsing
# But this also requires setting FOAM_FOAMUT
DOCS_DIR=$PWD CODE_SRC_DIR=<your/code/repo/folder> \
    CODE_TEST_DIR=<your/tests/folder> FOAM_FOAMUT=/tmp/ut \
    ./odw docs /tmp/foamcd.dbs
```

This will produce a tree under `content/en/api` for your libraries. Make sure to add a `content/en/api/_index.md` with the following frontmatter:
```yaml
---
title: API
layout: library # This is important
menu:           # Add this to main menu
  main:
    weight: 20
api_tags:
  - library
weight: 1
---
```

Another important task is to get the code authors right. **FoamCD** parses the authors from Git, so for each corresponding author, it's recommended to put a `content/en/contributors/<contibutor_alias>.md`. A typical frontmatter for such pages:
```yaml
---
title: Contributor's full name
shortTitle: main_alias
github: GithubAccount
linkedin: LinkedInProfileID
aliases:            # Possible aliases for this contributor in git logs
  - alias_1
  - email_1
---
```

### The blog section

The blog section is similar to `docs`, but lists the posts in reverse chronological order. The structure can be freely changed, but the [example blog](/blog) outlines a good starting point.

### Recording ADRs
