---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: li-yang-5h_dMuX_7RE-unsplash.webp
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Welcome 👋'
      subtitle: ''
      text: |-
        I am a statistician in the UCSF Department of Anesthesia. Prior to this, I obtained my PhD in biostatistics from UC Berkeley, where I worked on integrating causal inference and efficient non-/semi-parametric estimation for time-to-event clinical trials. I was lucky to enjoy diverse scientific collaborations with Novo Nordisk, the University of Copenhagen, and other members of the Joint Initiative for Causal Inference.
        
        My research interests lie primarily in unifying causal inference and estimation using machine learning under the umbrella of developing efficient and robust, assumption-lean inferential techniques tailored for the applied sciences. Broadly speaking, I am often motivated by methodological philosophy of targeted loss-based estimation approach to non- and semi-parametric inference (i.e. assumption-lean or model-agnostic perspective). While my applied science interests are diverse, I have recently been working on cardiovascular outcome trials. I am also deeply interested in developing open-source software to promote reproducibility, transparency, and data analysis “hygiene” in applied statistics and statistical data science.
        
        **Specialties:** 
          - Causal Inference 
          - Targeted Machine Learning
          - Statistical Computing and Reproducible Data Science
          
        **Interests** 
          MMA, Boxing, & Muay Thai; Wine & Regenerative Organic Viticulture, Stoic & Buddhist Ethics
        
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '1'
---
