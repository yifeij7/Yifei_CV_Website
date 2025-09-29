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
        My research centers on developing bioinspired multispectral imaging systems for cancer diagnostics and surgical guidance. Drawing inspiration from the mantis shrimp’s compound eye, I designed a camera capable of simultaneously capturing ultraviolet, visible, and near-infrared bands. This platform enables both labeled and label-free fluorescence imaging, with strong implications for advancing image-guided surgery and intraoperative pathology.
        
        Building on this foundation, I created a lensless UV–Visible–NIR microscopy system that replaces costly optics with a holographic diffuser. This approach not only reduces hardware complexity but also achieves higher resolution and single-shot three-dimensional imaging.

        To further enhance image reconstruction, I developed a 20-layer residual convolutional neural network tailored for multispectral demosaicing. Compared to conventional methods, this architecture significantly improves reconstruction fidelity, yielding higher-quality images critical for clinical translation.



    design:
      columns: '1'
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
