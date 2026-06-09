---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:

  - block: resume-biography-3
    content:
      username: me
      text: |-
        I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: About
        education: Education
        interests: Research Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: Research Interests
      text: |-
        - Machine Learning
        - Deep Learning
        - AI for Science
        - Scientific Modeling
        - Societal Impact of Technology
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
      count: 4
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: talks
    content:
      title: Recent Talks
      filters:
        folders:
          - events
      count: 4
    design:
      view: card
---