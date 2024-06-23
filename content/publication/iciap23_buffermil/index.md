---
title: 'Buffer-MIL: Robust Multi-instance Learning with a Buffer-Based Approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Luca Lumetti
  - Angelo Porrello
  - Federico Bolelli
  - Simone Calderara
  - Elisa Ficarra

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'


date: '2023-09-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Image Analysis and Processing 2023
publication_short: In *ICW*

abstract: Histopathological image analysis is a critical area of research with the potential to aid pathologists in faster and more accurate diagnoses. However, Whole-Slide Images (WSIs) present challenges for deep learning frameworks due to their large size and lack of pixel-level annotations. Multi-Instance Learning (MIL) is a popular approach that can be employed for handling WSIs, treating each slide as a bag composed of multiple patches or instances. In this work we propose Buffer-MIL, which aims at tackling the covariate shift and class imbalance characterizing most of the existing histopathological datasets. With this goal, a buffer containing the most representative instances of each disease-positive slide of the training set is incorporated into our model. An attention mechanism is then used to compare all the instances against the buffer, to find the most critical ones in a given slide. We evaluate Buffer-MIL on two publicly available WSI datasets, Camelyon16 and TCGA lung cancer, outperforming current state-of-the-art models by 2.2% of accuracy on Camelyon16.

# Summary. An optional shortened abstract.
summary: In this work we propose Buffer-MIL, which aims at tackling the covariate shift and class imbalance characterizing most of the existing histopathological datasets.

tags:
  - MIL
  - Covariance shift

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**ICIAP**](https://link.springer.com/chapter/10.1007/978-3-031-43153-1_1)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---