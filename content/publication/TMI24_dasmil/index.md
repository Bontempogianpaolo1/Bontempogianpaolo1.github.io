---
title: 'A Graph-Based Multi-Scale Approach With Knowledge Distillation for WSI Classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Federico Bolelli
  - Angelo Porrello
  - Simone Calderara
  - Elisa Ficarra 


# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'


date: '2023-11-28T00:00:00Z'
doi: 'https://doi.org/10.1109/TMI.2023.3337549'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In  IEEE Transactions on Medical Imaging
publication_short: In *TMI*

abstract: The usage of Multi Instance Learning (MIL) for classifying Whole Slide Images (WSIs) has recently increased. Due to their gigapixel size, the pixel-level annotation of such data is extremely expensive and time-consuming, practically unfeasible. For this reason, multiple automatic approaches have been raised in the last years to support clinical practice and diagnosis. Unfortunately, most state-of-the-art proposals apply attention mechanisms without considering the spatial instance correlation and usually work on a single-scale resolution. To leverage the full potential of pyramidal structured WSI, we propose a graph-based multi-scale MIL approach, DAS-MIL. Our model comprises three modules i) a self-supervised feature extractor, ii) a graph-based architecture that precedes the MIL mechanism and aims at creating a more contextualized representation of the WSI structure by considering the mutual (spatial) instance correlation both inter and intra-scale. Finally, iii) a (self) distillation loss between resolutions is introduced to compensate for their informative gap and significantly improve the final prediction. The effectiveness of the proposed framework is demonstrated on two well-known datasets, where we outperform SOTA on WSI classification, gaining a +2.7% AUC and +3.7% accuracy on the popular Camelyon16 benchmark.

# Summary. An optional shortened abstract.
summary:  we propose a graph-based multi-scale MIL approach, termed DAS-MI
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