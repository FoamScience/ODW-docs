---
title: Overview
description: Find out if this project is for you and your libraries!
weight: 1
---

This page is basically a recap of what would be a user-guide on how to use [ODW](https://github.com/FoamScience/ODW) to generate documentation sites for your own OpenFOAM projects. It's recommended that you follow the example structure too.

## What is ODW?

ODW is a [Hugo module](https://gohugo.io/hugo-modules/) with a special focus on generating API docs for OpenFOAM libraries in an "unattended" manner.

The [Hugo](https://gohugo.io) static site generator builds HTML docs from Markdown files. [FoamCD](https://github.com/FoamScience/FoamCD) parses and generates Markdown documentation for the OpenFOAM libraries (or any other C++ libs) users point to. This allows to host such websites at no cost on multiple platforms (Github Pages being our main target) and the generation of the docs can be just another step in the user's CI/CD workflow!

The promise is that users will only have to write the docs in Markdown syntax, and they get automatically-generated API and unit testing documentation updates as their code changes. Having the documentation in Markdown format also makes it re-usable in a couple of other places.

{{< alert color="warning" >}}
One common issue with the API documentation is reflecting certain code entity states, like **deprecation**. ODW takes great care to expose this information to API users in a meaningful way. For example, deprecations are detected through both in-line comments and compiler attributes, and the respective entities are flagged as such!
{{< /alert >}}

## Why would I want to use ODW?

* **What is it good for?**: Low-friction, extensive, documentation written in Markdown for OpenFOAM libraries.

* **What is it not good for?**:
  - Even though this is mainly an API documentation tool, it doesn't try to replace good IDE setup;
    users are not expected to consult the API docs so they can find functions or classes. What we strive for here, is:
    - to provide a comprehensive understanding of the language features used, hence the focus on C++ and DSL features in API docs.
    - to provide an opportunity for contextual learning, hence the focus on exposing DSL features that wouldn't be recognized by an IDE.
    - to provide a way to flatten the learning curve for new developers, hence the support for ADRs, unit tests and blogs.
  - The OpenFOAM build system (wmake) is heavily relied on, so PRs would be needed to switch/support other build systems.
  - If your idea of documentation doesn't confine to "simple Markdown pages", this is probably not for you.

* **What is it *not yet* good for?**: There is a [ROADMAP](https://github.com/FoamScience/FoamCD/blob/main/ROADMMAP.md) that details not-yet-supported features.

## Where should I go next?

We have prepared a check-list for you to go through if you decide to adopt ODW to manager your project's documentation:

1. [ ] **Pre-requisite:** Get familiarized with [Hugo](https://gohugo.io/getting-started/quick-start/): the important sections are "Add content" and "Configure the site".
1. [ ] Create your [first documentation website](/docs/getting-started/first-docs-website):
    - [ ] Adapt your [hugo.toml](https://github.com/FoamScience/ODW-docs/blob/main/hugo.toml) configuration file to suit your needs.
    - [ ] Explore [docs folder](https://github.com/FoamScience/ODW-docs/tree/main/content/en/docs) from this repository if you want to include a "Getting-Started" section. You are free in what structure you opt for, just keep an eye on the "time-to-read" on each page!
    - [ ] Setup the first [blog post](https://github.com/FoamScience/ODW/tree/main/content/en/blog). Maybe start with announcing the switch to ODW! Also, we recommend to exploit the discussions section to share technical updates with your community.
    - [ ] Generate API and (optionally) unit-test docs generation
1. [ ] Adapt the [GA workflow configuration](https://github.com/FoamScience/ODW-docs/blob/main/.github/workflows/gh-pages.yml) to reflect your needs (e.g. the URL to publish to) so you can deploy your site on each commit/release.
    - [ ] Don't forget to turn on Pages deployments from `gh-pages` branch in your repository settings.
1. [ ] The [Example page](/docs/getting-started/example-page) can help accelerate learning how to write the markdown content.

Congrats! That's all that is needed. Now expand on your content, Have fun!
