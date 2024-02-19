# Post Bootcamp Society Prototype <!-- omit in toc -->

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<details>
<summary>Table of Contents</summary>

- [Overview](#overview)
- [Contribution Guideline](#contribution-guideline)
  - [Dev Containers](#dev-containers)
  - [MkDocs](#mkdocs)
  - [How to contribute](#how-to-contribute)

</details>
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Overview

This is a prototype of the Post Bootcamp Society website to help brige the gap from graduation to first job.

This prototype aims to have the following:

- **Core Guides:** A set of essential guides to help graduates take their captstone projects to the next level. This should only contain simple, easy to follow guides that are essential for graduates to know.
- **Community Guides:** Community contributed guides to help graduates with the next steps in their career. Each user has their own directory to contribute to.

## Contribution Guideline

### Dev Containers

This repository is set up to use [dev containers](https://containers.dev/), to which one can use [Codespaces](https://github.com/features/codespaces) or any IDE that supports dev containers.

### MkDocs

[MkDocs](https://www.mkdocs.org/) is a static site generator that's geared towards project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.

### How to contribute

1. Fork the repository and create a new branch
2. Make your changes under `/docs/core` for core guides and `/docs/community` for community guides.
3. Add your changes to the `mkdocs.yml` file under the `nav` section.
4. Run `mkdocs serve` to see your changes locally.
5. Push your changes to your fork and create a pull request.