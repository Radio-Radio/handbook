---
title: "Contributing documentation"
description: "Where is the documentation and how to contribute."
category: organization
lang: en
ref: documenting
order: 100
version: 1
---

There are currently 4 sources of documentation for Symbol. Feel free to jump to the one you are interested in.

- [Technical documentation](#technical-documentation): Tool guides, developer tutorials and SDK reference guides.
- [Syndicate documentation](#syndicate-documentation): The syndicate's philosophy, educational material and internal organization guidelines.
- [Working documentation](#working-documentation): Meeting minutes, Community logs, stuff that changes often.
- [NIS1 documentation](#nis1-documentation): Old NIS1 guides, pending assimilation into the Symbol technical docs.

## Technical documentation

**Site** | [docs.symbolplatform.com](https://docs.symbolplatform.com)
**Source repo** | [github.com/symbol/symbol-docs](https://github.com/symbol/symbol-docs)
**Host** | [GitHub pages](https://github.com/symbol/symbol.github.io)
**Engine** | [Sphinx](https://www.sphinx-doc.org)
**Format** | [reStructuredText](https://docutils.sourceforge.io/rst.html)
**Intended readers** | The world at large.
**Intended writers** | The Symbol technical writers.
**Editing workflow** | Git-based: Check out the source repository, make modifications and submit pull requests.
**Localization** | [Transifex](https://www.transifex.com/nemtech/symboldocs/)
{: .info_table }

This is the main technical reference. It contains (or will contain):

- **User guides** for the different tools (Wallet, CLI, Explorer, etc.), intended for non-heavily-technical readers, including screenshots and step-by-step instructions on how to solve common problems.
- **Developer tutorials** with source code examples in different languages, organized by topics. Ranging from Getting Started to in-depth guides on specific topics.
- **Concept definitions** required to understand the Symbol protocol.
- **Technical reference** guides describing every API and REST endpoint.

Due to the complexity of the technical content, Sphinx (and reStructuredText) is used instead of the simpler MarkDown format. This allows easily embedding multi-language (tabbed) code snippets, for example.

## Syndicate documentation

**Site** | [docs.symbolplatform.com/handbook](https://docs.symbolplatform.com/handbook)
**Source repo** | [github.com/symbol/handbook](https://github.com/symbol/handbook/tree/gh-pages)
**Host** | [GitHub pages](https://github.com/symbol/handbook/tree/gh-pages)
**Engine** | [Jekyll](https://jekyllrb.com/)
**Format** | [Kramdown](https://kramdown.gettalong.org/) (A flavor of Markdown)
**Intended readers** | Syndicate members and contributors.
**Intended writers** | Syndicate members and contributors.
**Editing workflow** | Edit pages directly on GitHub or HackMD and submit a pull request.
**Localization** | Manual. There is a folder for each language and anybody can provide translations.
{: .info_table }

1. Pages with the ![hackmd-github-sync-badge](https://hackmd.io/afJzrT-RTAamp4uQTTLhHw/badge){: .inline_image } badge are maintained directly on [HackMD](https://hackmd.io/team/syndicate). Edit them there and push the changes to GitHub instead of the other way around.

## Working documentation

**Site** | [hackmd.io/team/syndicate](https://hackmd.io/team/syndicate)
**Source repo** | [hackmd.io/team/syndicate](https://hackmd.io/team/syndicate)
**Host** | [hackmd.io/team/syndicate](https://hackmd.io/team/syndicate)
**Engine** | HackMD
**Format** | [Markdown](https://www.markdownguide.org/)
**Intended readers** | Syndicate members.
**Intended writers** | Syndicate members.
**Editing workflow** | Edit pages directly on HackMD.
**Localization** | None
{: .info_table }

## NIS1 documentation

**Site** | [docs.nem.io/en](https://docs.nem.io/en) <br> [nemproject.github.io](https://nemproject.github.io/)
**Source repo** | ?
**Host** | ?
**Engine** | ?
**Format** | ?
**Intended readers** | The world at large.
**Intended writers** | The Symbol technical writers.
**Editing workflow** | ?
**Localization** | ?
{: .info_table }
