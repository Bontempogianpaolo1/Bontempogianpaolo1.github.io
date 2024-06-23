---
title: 'DAS-MIL: Distilling Across Scales for MIL Classification of Histological WSIs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Angelo Porrello
  - Federico Bolelli
  - Simone Calderara
  - Elisa Ficarra 


# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'


date: '2023-10-01T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-031-43907-0_24'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In  Medical Image Computing and Computer Assisted Intervention 
publication_short: In *MICCAI*

abstract: The adoption of Multi-Instance Learning (MIL) for classifying Whole-Slide Images (WSIs) has increased in recent years. Indeed, pixel-level annotation of gigapixel WSI is mostly unfeasible and time-consuming in practice. For this reason, MIL approaches have been profitably integrated with the most recent deep-learning solutions for WSI classification to support clinical practice and diagnosis. Nevertheless, the majority of such approaches overlook the multi-scale nature of the WSIs; the few existing hierarchical MIL proposals simply flatten the multi-scale representations by concatenation or summation of features vectors, neglecting the spatial structure of the WSI. Our work aims to unleash the full potential of pyramidal structured WSI; to do so, we propose a graph-based multi-scale MIL approach, termed DAS-MIL, that exploits message passing to let information flows across multiple scales. By means of a knowledge distillation schema, the alignment between the latent space representation at different resolutions is encouraged while preserving the diversity in the informative content. The effectiveness of the proposed framework is demonstrated on two well-known datasets, where we outperform SOTA on WSI classification, gaining a +1.9% AUC and +3.3% accuracy on the popular Camelyon16 benchmark.

# Summary. An optional shortened abstract.
summary:  We introduce Neuro-Symbolic Continual Learning
tags:
  - MIL
  - Histology

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/aimagelab/mil4wsi'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**MICCAI**](https://link.springer.com/chapter/10.1007/978-3-031-43907-0_24)'
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