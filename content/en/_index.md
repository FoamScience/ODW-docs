---
title: ODW
---

{{< blocks/cover title="Your template for documenting OpenFOAM libraries" image_anchor="top" height="full" >}}
Effortless, versioned docs for your OpenFOAM code—generated in one command.

<a class="btn btn-lg btn-secondary me-3 mb-4" href="/docs">
  Get Started <i class="fas fa-arrow-alt-circle-right ms-2"></i>
</a>
<a class="btn btn-lg btn-primary me-3 mb-4" href="https://github.com/FoamScience/OpenFOAMDocsWebpages">
  Use as Hugo module <i class="fab fa-github ms-2 "></i>
</a>
{{< blocks/link-down color="info" >}}
{{< /blocks/cover >}}

{{% blocks/lead color="primary" %}}
ODW (OpenFOAM-Docs-Webpages) is a lightweight Hugo module designed to create clean, versioned documentation websites for OpenFOAM libraries.

With a single command call, it can generate up-to-date API docs and unit test coverage — automatically synced with your codebase.
{{% /blocks/lead %}}

{{% blocks/section color="dark" type="row" %}}
{{% blocks/feature icon="fa-lightbulb" title="Hugo" url="https://gohugo.io/" %}}

We use **Hugo** to instantly build a full-featured documentation site—ready for GitHub Pages—with support for blogs, ADRs, API docs, unit tests, and tutorials.  
Write in Markdown (with LaTeX + Mermaid support) for a smooth, developer-friendly experience.
{{% /blocks/feature %}}


{{% blocks/feature icon="fab fa-github" title="FoamCD" url="https://github.com/FoamScience/FoamCD" %}}
API docs are auto-generated with **FoamCD**, a modern tool built to expose both C++ standard features and OpenFOAM-specific DSLs (with a few more DSL features from other frameworks).
It's modular too—you can swap it out easily. We've hopped through Doxygen, Hyde, and Standardese, but FoamCD fit the ODW vision best.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-github" title="FoamUT" url="https://github.com/FoamScience/foamUT" %}}

Unit test docs are auto-generated and linked to related API classes—if you write tests using **foamUT** (Catch2).  
This step is optional, but we strongly recommend adding unit tests to get the most out of the documentation pipeline.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead byline="By::" %}}

# API and Unit tests docs for the lazy
{.text-center}

As a modern alternative to Doxygen, [**FoamCD**](https://github.com/FoamScience/FoamCD) generates API docs as Markdown—highlighting C++ features and OpenFOAM-specific DSL patterns. It preserves custom content between builds and uses cached index databases to speed up and enrich doc generation, automatically linking classes to their unit tests.
{.text-center}

**FoamCD** relies primarily on **libclang** to parse the AST—so anything Clang supports should work out of the box. While inline comments are parsed as docs, we recommend keeping important notes in dedicated Markdown files (with full LaTeX and Mermaid support).
{.text-center}

{{% /blocks/lead %}}

{{% blocks/lead %}}

# Wiki-like docs
{.text-center}

The same Markdown system powers custom pages like **“Getting Started”** or **“FAQ”**, built from your own content. You get full access to all **Hugo** and **Docsy** shortcodes and features for flexible, styled documentation.
{.text-center}

{{% /blocks/lead %}}

{{% blocks/section %}}

# A Blog and an ADR backlog
{.text-center}

I like to track project progress through a **DevLog**—a great way to share evolution, insights, and lessons learned. Publishing it not only helps others, but also improves project visibility through more searchable, detailed content.
{.text-center}

**Decision Records** are managed as a dedicated content type, making it easier for new contributors to onboard while clearly conveying the project's intentions and design philosophy.
{.text-center}

{{% /blocks/section %}}
