---
title: 'Probaverse'
date: 2023-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: cta-image-paragraph
    id: intro
    content:
      items:
        - title: "The Probaverse Project"
          text: |-
            **An open-source ecosystem for probabilistic thinking.**

            Probaverse is a community-driven effort to rethink how we work with probability distributions, uncertainty, and reproducible statistical workflows.

            At its core is a simple idea: distributions should be programmable objects—composable, transformable, and grounded in real-world data.

            The project is evolving, with new tools, ideas, and patterns emerging over time.

            Install with R:

            ```r
            install.packages("probaverse")
            ```
          image: probaverse-large.png
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"

  - block: collection
    id: packages
    content:
      count: 0
      order: asc
      page_type: r-pak
      sort_by: Title
      subtitle: ""
      title: Packages
      text: |-
        The probaverse is organized around a coherent workflow:
        define distributions, transform them, fit them to data, and extend to multivariate systems.
      filters:
        tag: probaverse-core
    design:
      view: package-list
      columns: "1"

  - block: collection
    id: packages-upcoming
    content:
      count: 0
      order: asc
      page_type: r-pak
      sort_by: Title
      subtitle: ""
      title: Upcoming
      filters:
        tag: probaverse-upcoming
    design:
      view: package-list
      columns: "1"

  - block: markdown
    id: the-project
    content:
      title: "The Project"
      text: |-
        Probaverse is an open, evolving project built around a shared set of principles:

        - **Clarity** — statistical ideas should be explicit and understandable
        - **Composability** — complex models should be built from simple parts
        - **Reproducibility** — workflows should be transparent and repeatable
        - **Extensibility** — users should be able to define and share their own tools

        The project welcomes contributions, ideas, and discussion as it grows.
    design:
      columns: "1"

  - block: markdown
    id: get-involved
    content:
      title: "Get involved"
      text: |-
        - Explore the [packages and documentation](#packages)
        - Read updates on the [Probaverse blog](/post/)
        - Follow development and contribute on [GitHub](https://github.com/probaverse)
        - Share ideas, use cases, or extensions

        Probaverse is not just a set of tools—it is an ongoing effort to build a better way to work with uncertainty.
    design:
      columns: "1"
---
