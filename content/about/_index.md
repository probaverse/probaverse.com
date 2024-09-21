---
title: 'About'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:

  ## ------- SECTION: slogan -------
  - block: hero
    content:
      title: Expertise in Predicting Rare, High-Impact Events
      #text: 🧱 EASY. FREE (OPEN SOURCE). NO-CODE  🧱
      #primary_action:
      #  text: Get Started
      #  url: https://hugoblox.com/templates/
      #  icon: rocket-launch
      #secondary_action:
      #  text: Read the docs
      #  url: https://docs.hugoblox.com
      #announcement:
      #  text: "Announcing the release of version 1."
      #  link:
      #    text: "Read more"
      #    url: "/blog/"
    #design:
    #  spacing:
    #    padding: ["1rem", 0, "1rem", 0] # [0, 0, 0, 0] ["5rem", 0, "5rem", 0]
    #    #margin: [0, 0, 0, 0]
    #  # For full-screen, add `min-h-screen` below
    #  css_class: "dark"
    #  background:
    #    color: "navy"
    #    image:
    #      # Add your image background to `assets/media/`.
    #      filename: bg-triangles.svg
    #      filters:
    #        brightness: 0.5
  
  ## ------- SECTION: bullets -------
  - block: features
    id: features
    content:
      #title: Features
      text: I combine advanced statistical and data science techniques to build large probabilistic models, particularly for extreme events. My work involves creating innovative methodologies to address gaps in the literature and applying these techniques in practical, real-world scenarios. My goal is to collaborate on projects that demand innovation and to bring clarity to complex problems. 
      items:
        - name: Statistics
          icon: magnifying-glass
          description: Employ a broad range of methodologies, including probability theory, machine learning, extreme value theory, copula models, and uncertainty analysis to tackle unique challenges.
        - name: Computation
          icon: bolt
          description: Maintain high standards of computational hygiene with defensive programming, version control, and data provenance for well-documented, reproducible codebases.
        - name: Project Management
          icon: sparkles
          description: Tailor model complexity to project needs, starting simple and adding layers only as necessary to achieve optimal solutions.
        - name: Communication
          icon: code-bracket
          description: Engage in two-way transfer of knowledge with domain experts to align models with practical needs and communicate the results meaningfully.
  
  - block: stats
    content:
      items:
        - statistic: "github"
          description: Vincenzo's github page
        - statistic: "LinkedIn"
          description: |
            GitHub stars  
            since 2016
        - statistic: "OrcID"
          description: |
            Discord community  
            for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  
  ## ------- SECTION: featured work -------
  - block: collection
    content:
      count: 4
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
      page_type: project
      subtitle: ""
      text: "Vincenzo works on real-world projects for clients, and conducts research for applications. Here are some examples."
      title: Featured Work
    design:
      spacing:
        padding:
        - 10rm
        - 0
        - 0
        - 0
      view: article-grid
    id: featured_work
  
  ## ------- SECTION: testimonials -------
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  
  ## ------- SECTION: Publications -------
  - block: collection
    content:
      title: Scholarly Publications
      text: "Articles in scientific journals, proceedings, and preprints."
      filters:
        folders:
          - publication
        #exclude_featured: false
        #featured_only: true
    design:
      view: citation
  
  ## ------- SECTION: Experience -------
  - block: resume-experience
    content:
      username: admin
    design:
      date_format: January 2006
      is_education_first: false

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Need an innovative solution?
          text: I am always interested in hearing about a need for innovative solutions. Reach out on LinkedIn.
          feature_icon: check
          features:
            - "Multivariate extremes"
            - "Risk-informed decision making"
            - "Mutliple application areas"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Get Started
            url: https://hugoblox.com/templates/
        - title: For applications in the applied earth sciences
          text: I work on applications such as hydrology, climate science, and geohazards with BGC Engineering. Reach out to me there. 
          #feature_icon: bolt
          #features:
          #  - "Dedicated support channel"
          #  - "3,000+ users on Discord"
          #  - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  
  #  - block: stats
  #  content:
  #    items:
  #      - statistic: "1M+"
  #        description: |
  #          Websites built  
  #          with Hugo Blox
  #      - statistic: "10k+"
  #        description: |
  #          GitHub stars  
  #          since 2016
  #      - statistic: "3k+"
  #        description: |
  #          Discord community  
  #          for support
  #  design:
  #    # Section background color (CSS class)
  #    css_class: "bg-gray-100 dark:bg-gray-900"
  #    # Reduce spacing
  #    spacing:
  #      padding: ["1rem", 0, "1rem", 0]
  
  #- block: cta-card
  #  content:
  #    title: Build your future-proof website
  #    text: As easy as 1, 2, 3!
  #    button:
  #      text: Get Started
  #      url: https://hugoblox.com/templates/
  #  design:
  #    card:
  #      # Card background color (CSS class)
  #      css_class: "bg-primary-700"
  #      css_style: ""
---
