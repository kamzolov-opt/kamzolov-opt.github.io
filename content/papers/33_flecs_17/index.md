---
title: 'FLECS: A Federated Learning Second-Order Framework via Compression and Sketching'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Artem Agafonov
  - admin
  - Rachael Tappenden
  - Alexander Gasnikov
  - Martin Takáč
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-06-04'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "preprint, under review"
#publication_short: In *JOTA*

abstract: Inspired by the recent work FedNL (Safaryan et al, FedNL Making Newton-Type Methods Applicable to Federated Learning), we propose a new communication efficient second-order framework for Federated learning, namely FLECS. The proposed method reduces the high-memory requirements of FedNL by the usage of an L-SR1 type update for the Hessian approximation which is stored on the central server. A low dimensional `sketch' of the Hessian is all that is needed by each device to generate an update, so that memory costs as well as number of Hessian-vector products for the agent are low. Biased and unbiased compressions are utilized to make communication costs also low. Convergence guarantees for FLECS are provided in both the strongly convex, and nonconvex cases, and local linear convergence is also established under strong convexity. Numerical experiments confirm the practical benefits of this new FLECS algorithm.
          
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - First-Order Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:2206.02009
   url: https://arxiv.org/abs/2206.02009
   
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
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
