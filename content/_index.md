---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ""
    design:
      css_class: light
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
    avatar:
      size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
      shape: circle # Options: circle (default), square, rounded

  - block: markdown
    content:
      title: '🔬 My Research'
      subtitle: ''
      text: |-
        My work lies at the intersection of biostatistics, real-world evidence, and clinical research methodology. I am particularly interested in advancing statistical approaches that improve the use of observational and clinical trial data to support healthcare decision-making and regulatory science.

        I am currently a Senior Biostatistician at Biotrial Biometrics, where I lead scientific initiatives in real-world evidence and contribute to the development and dissemination of RWE expertise through collaborations, working groups, and training activities.

        I am always open to scientific discussion and collaboration in these areas 😃
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
    design:
      view: article-grid
      columns: 2
---