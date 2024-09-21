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
        - title: Probaverse
          text: The probaverse is a suite of tools in R for exploring the full space of possible outcomes in an analysis. It elevates probability distributions as tangible objects that realistically represent your system.
          # Upload image to `assets/media/` and reference the filename here
          image: probaverse-large.png
          feature_icon: check
          features:
            - Build flexible distributions that capture system behaviour.
            - Transform and refine distributions to reflect observations.
            - Assemble multivariate models for deeper insights.
          button:
            text: Installation Instructions
            url: /#get_started
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"

  ## ------- SECTION: testimonials -------
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Vincenzo Coia"
          #username: '@geo'
          # Image path relative to assets/media/ folder
          image_filename: tweets/GitHub.png
          role: "Statistical Data Scientist"
          link: "https://vincenzocoia.com"
          # Upload image to `assets/media/` and reference the filename here
          image: "vincenzo-smiley-headshot.jpg"
          text: "Uncertainty is inevitable in almost all complex systems, from financial markets to environmental systems to the human body. The probaverse offers a way to accept uncertainty, model it, and use those insights to make smarter, more informed decisions."
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  

  ## ------- SECTION: packages -------
  - block: collection
    content:
      count: 99999
      filters:
        author: ""
        category: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
        tag: ""
      offset: 0
      order: desc
      sort_by: 'Date'
      page_type: r-pak
      subtitle: ""
      text: |-
        {{% callout warning %}}
        Packages will be under active development throughout fall 2024. In some cases, prototypes are available for installation through github.
        {{% /callout %}}
      title: Packages
    design:
      spacing:
        padding:
        - 10rm
        - 0
        - 0
        - 0
      view: article-list  # date-title-summary
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

  
  - block: cta-card
    id: get_started
    content:
      title: Get started with the probaverse.
      text: |-
        Currently, the probaverse can be installed by each package individually, although only three packages are available as prototypes:
        ```
        remotes::install_github("probaverse/distionary")
        remotes::install_github("probaverse/distplyr")
        remotes::install_github("probaverse/famish")
        ```
      #button:
      #  text: Find it on GitHub
      #  url: https://github.com/probaverse/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700" # "bg-purple-500" # "bg-primary-700"
        css_style: ""
---
