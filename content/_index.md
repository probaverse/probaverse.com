---
title: 'Probaverse'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:

  ## ------- SECTION: slogan -------
  - block: cta-image-paragraph
    id: intro
    content:
      items:
        - title: The modern ecosystem for probabilistic thinking.
          text: |-
            A cohesive set of open-source tools for working with probability distributions, uncertainty, and reproducible statistical workflows.
   
            Install with R by running
            ```
            install.packages("probaverse")
            ```
          # Upload image to `assets/media/` and reference the filename here
          image: probaverse-large.png
          # feature_icon: check
          # features:
          #   - Build flexible distributions that capture system behaviour.
          #   - Transform and refine distributions to reflect observations.
          #   - Assemble multivariate models for deeper insights.
          # button:
          #   text: Installation Instructions
          #   url: /#get_started
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"

  ## ------- SECTION: packages -------
  - block: collection
    content:
      # count: 99999
      # filters:
      #   author: ""
      #   category: ""
      #   exclude_featured: false
      #   exclude_future: false
      #   exclude_past: false
      #   publication_type: ""
      #   tag: ""
      # offset: 0
      # order: desc
      # sort_by: 'Date'
      page_type: r-pak
      subtitle: ""
      title: Packages
    design:
      view: card
      # spacing:
      #   padding:
      #   - 10rm
      #   - 0
      #   - 0
      #   - 0
      #view: date-title-summary # card # date-title-summary  # article-list
    id: r_pkgs


  ## ------- SECTION: Recent Posts -------
  #- block: collection
  #  content:
  #    count: 2
  #    filters:
  #      author: ""
  #      category: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #      tag: ""
  #    offset: 0
  #    order: desc
  #    page_type: post
  #    subtitle: ""
  #    text: "Explore more about how the probaverse philosophy can transform the way you think about data analysis."
  #    title: Probaverse Blog
  #  design:
  #    spacing:
  #      padding:
  #      - 0
  #      - 0
  #      - 0
  #      - 0
  #    view: article-grid # article date-title-summary
  #  id: news

  
  ## ------- SECTION: governance -------
  - block: markdown
    id: about
    content:
      title: 'Governance'
      subtitle: ''
      text: |-
        Probaverse is a community-driven open ecosystem.
        Development is led by contributors, with principles that emphasize
        clarity, reproducibility, and conceptual coherence.
    design:
      columns: '1'
---
