---
title: 'Convolutional neural network advances in demosaicing for fluorescent cancer imaging with color–near-infrared sensors'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yifei Jin
  - Borislav Kondov
  - Goran Kondov
  - Sunil Singhal
  - Shuming Nie
  - Viktor Gruev

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In Journal of biomedical optics

Abstract: 
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/resume.pdf'
url_source: 'https://www.spiedigitallibrary.org/journals/journal-of-biomedical-optics/volume-29/issue-7/076005/Convolutional-neural-network-advances-in-demosaicing-for-fluorescent-cancer-imaging/10.1117/1.JBO.29.7.076005.full'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

Single-chip imaging devices featuring vertically stacked photodiodes and pixelated spectral filters are advancing multi-dye imaging methods for cancer surgeries, though this innovation comes with a compromise in spatial resolution. To mitigate this drawback, we developed a deep convolutional neural network (CNN) aimed at demosaicing the color and near-infrared (NIR) channels, with its performance validated on both pre-clinical and clinical datasets. We introduce an optimized deep CNN designed for demosaicing both color and NIR images obtained using a hexachromatic imaging sensor. A residual CNN was fine-tuned and trained on a dataset of color images and subsequently assessed on a series of dual-channel, color, and NIR images to demonstrate its enhanced performance compared with traditional bilinear interpolation. Our optimized CNN for demosaicing color and NIR images achieves a reduction in the mean square error by 37% for color and 40% for NIR, respectively, and enhances the structural dissimilarity index by 37% across both imaging modalities in pre-clinical data. In clinical datasets, the network improves the mean square error by 35% in color images and 42% in NIR images while enhancing the structural dissimilarity index by 39% in both imaging modalities.