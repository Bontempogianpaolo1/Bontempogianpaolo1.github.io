---
title: 'Enhancing PFI Prediction with GDS-MIL: A Graph-based Dual Stream MIL Approach'

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

abstract: Whole-Slide Images (WSI) are emerging as a promising resource for studying biological tissues, demonstrating a great potential in aiding cancer diagnosis and improving patient treatment. However, the manual pixel-level annotation of WSIs is extremely time-consuming and practically unfeasible in real-world scenarios. Multi-Instance Learning (MIL) have gained attention as a weakly supervised approach able to address lack of annotation tasks. MIL models aggregate patches (e.g., cropping of a WSI) into bag-level representations (e.g., WSI label), but neglect spatial information of the WSIs, crucial for histological analysis. In the High-Grade Serous Ovarian Cancer (HGSOC) context, spatial information is essential to predict a prognosis indicator (the Platinum-Free Interval, PFI) from WSIs. Such a prediction would bring highly valuable insights both for patient treatment and prognosis of chemotherapy resistance. Indeed, NeoAdjuvant ChemoTherapy (NACT) induces changes in tumor tissue morphology and composition, making the prediction of PFI from WSIs extremely challenging. In this paper, we propose GDS-MIL, a method that integrates a state-of-the-art MIL model with a Graph ATtention layer (GAT in short) to inject a local context into each instance before MIL aggregation. Our approach achieves a significant improvement in accuracy on the “Ome18” PFI dataset. In summary, this paper presents a novel solution for enhancing PFI prediction in HGSOC, with the potential of significantly improving treatment decisions and patient outcomes.

# Summary. An optional shortened abstract.
summary:  we propose GDS-MIL, a method that integrates a state-of-the-art MIL model with a Graph ATtention layer (GAT in short) to inject a local context into each instance before MIL aggregation, usefull for PFI prediction

tags:
  - MIL
  - Histology

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
  caption: 'Image credit: [**ICIAP**](https://link.springer.com/chapter/10.1007/978-3-031-43148-7_46)'
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