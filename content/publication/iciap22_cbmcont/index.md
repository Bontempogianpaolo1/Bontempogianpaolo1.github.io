---
title: 'Catastrophic Forgetting in Continual Concept Bottleneck Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Emanuele Marconato
  - admin
  - Stefano Teso
  - Elisa Ficarra
  - Simone Calderara
  - Andrea Passerini


# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'


date: '2023-09-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Image Analysis and Processing 2023
publication_short: In *ICIAP*

abstract: Almost all Deep Learning models are dramatically affected by Catastrophic Forgetting when learning over continual streams of data. To mitigate this problem, several strategies for Continual Learning have been proposed, even though the extent of the forgetting is still unclear. In this paper, we analyze Concept Bottleneck (CB) models in the Continual Learning setting and we investigate the effect of high-level features supervision on Catastrophic Forgetting at the representation layer. Consequently, we introduce two different metrics to evaluate the loss of information on the learned concepts as new experiences are encountered. We also show that the obtained Saliency maps remain more stable with the attributes supervision. 

# Summary. An optional shortened abstract.
summary:  we analyze Concept Bottleneck (CB) models in the Continual Learning.

tags:
  - Continual Learning
  - XAI

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