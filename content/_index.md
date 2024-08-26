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
        text: Download Resume
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: uiuc.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 Research Abstract'
      subtitle: ''
      text: |-
        My research focuses on developing a multispectral camera system for labeled and label-free fluorescence cancer imaging. Inspired by the unique structure of the mantis shrimp's eye, this camera can simultaneously capture images across the UV, visible, and NIR spectrums. The system has significant implications for advancing image-guided surgery and intraoperative pathology. Based on the bioinspired camera, I also developed a lensless microscopy within the UV-Visible-NIR spectrum. By replacing expensive optical lenses with a holographic diffuser, the lensless microscopy achieves even higher resolution and enables three-dimensional imaging with a single shot. To optimize the bioinspired camera's image demosaicing, I designed and trained a 20-layer convolutional network with residual learning, significantly enhancing reconstructed image quality compared to traditional methods.



    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Projects
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - citation
        exclude_featured: false
    design:
      view: citation
 

---
