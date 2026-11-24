---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/cv.pdf
    design:
      css_class: ocean-biography
      background:
        color: "#b9edf2"
        image:
          # Add your image background to `assets/media/`.
          filename: bright-ocean.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  #- block: markdown
  #  content:
  #    title: '📚 My Research'
  #    subtitle: ''
  #    text: |-
  #      Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #      I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
  #      Please reach out to collaborate 😃
  #  design:
  #    columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications and Preprints
      text: ""
      # Display all publications and preprints.
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
