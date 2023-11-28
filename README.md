[![Netlify Status](https://api.netlify.com/api/v1/badges/6594a2dd-776a-40a0-a6c5-7ea2dc7c664e/deploy-status)](https://app.netlify.com/sites/zen-bhaskara-590b05/deploys)
![GitHub license](https://img.shields.io/github/license/bowman2001/perplex)
![GitHub issues](https://img.shields.io/github/issues/bowman2001/perplex)
![GitHub closed issues](https://img.shields.io/github/issues-closed/bowman2001/perplex?color=green)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=bowman2001_perplex&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=bowman2001_perplex)

# Perplex Theme

Perplex is a Markdown documentation and multi-purpose theme for Hugo (extended version for WEBP). No other software is required to start with a new project.

[**The documentation**][doc] is also the **demonstration site**. If you want to get started right away visit the [workflow introduction][intro].

## Features

All kinds of pages are rendered into the same coherent **fluid-responsive layout grid**. The detailed typographic design is based on classic principles and techniques. The theme can generate

- large documentation with up to three menu levels

- blog postings

- a news stream

- author pages

- card previews

The default styling of Markdown content is **optimized for good legibility** and there are many options to further enhance the layout. **Light & dark** modes follow the setting of the OS environment automatically.

**All navigational elements** to sift through the content as fast as possible are generated from data in the frontmatter:

  - Site menu at the top

  - Sidebar menu for documentation

  - Taxonomies

  - Page-to-page links

  - Breadcrumbs

Google’s [Material Symbols][ms] and [Simple Icons][si] for brands can be included by their identifiers. Material Symbols automatically show in all navigational elements of the documentation. All icon sets can also be used as Markdown content (using shortcodes).

The **appearance of images** can be controlled to a large extent. The theme handles their preprocessing and the generation of all the needed variants. They are delivered smoothly with [Lazysizes][ls] and without layout shifts.

To offer a **full-text search** the theme is prepared to generate and self-host indices with the fast library [Pagefind][pf] (the additional installation of its open-source node package is required).

Sites built with this theme are **very fast and cost-effective**. Image sets are highly optimized to minimize the needed bandwidth (and loaded lazily), fonts are split into small packages, and icons are embedded inline.

[doc]: https://perplex.desider.at/doc
[intro]: https://perplex.desider.at/doc/intro/workflow/
[ms]: https://fonts.google.com/icons 
[si]: https://simpleicons.org
[ls]: https://github.com/afarkas/lazysizes
[pf]: https://pagefind.app
