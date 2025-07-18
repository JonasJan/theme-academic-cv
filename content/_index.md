---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: system
      background:
        color: '#185a5c'
        text_color_light: true
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
      count: 0
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent Talks
      filters:
        folders:
          - talks
      count: 0
    design:
      view: citation
  - block: markdown
    id: service
    content:
      title: 'Service'
      subtitle: ''
      text: |-
        #### Reviewing
        - Crypto 2023
        - Eurocrypt 2024
        - TCC 2023
        - PKC 2025
        - ACNS 2025
        
        ####
    design:
      columns: '2'
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        📧 firstname.lastname@rub.de <br>🏢 Building MC, Room 0/20, Universit&auml;tsstr. 140, 44801 Bochum
    design:
      background:
        color: '#185a5c'
        text_color_light: true
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
