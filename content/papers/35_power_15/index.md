---
title: 'The Power of First-Order Smooth Optimization for Black-Box Non-Smooth Problems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Alexander Gasnikov
  - Anton Novitskii
  - Vasilii Novitskii
  - Farshed Abdukhakimov
  - admin
  - Aleksandr Beznosikov
  - Martin Takáč
  - Pavel Dvurechensky
  - Bin Gu
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-01-28'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 39th International Conference on Machine Learning (ICML 2022)* 
publication_short: In *ICML 2022*

abstract: Gradient-free/zeroth-order methods for black-box convex optimization have been extensively studied in the last decade with the main focus on oracle calls complexity. In this paper, besides the oracle complexity, we focus also on iteration complexity, and propose a generic approach that, based on optimal first-order methods, allows to obtain in a black-box fashion new zeroth-order algorithms for non-smooth convex optimization problems. Our approach not only leads to optimal oracle complexity, but also allows to obtain iteration complexity similar to first-order methods, which, in turn, allows to exploit parallel computations to accelerate the convergence of our algorithms. We also elaborate on extensions for stochastic optimization problems, saddle-point problems, and distributed optimization.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Zero-Order Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
# - name: arXiv:2103.14392
#   url: https://arxiv.org/abs/2103.14392
   
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://proceedings.mlr.press/v162/gasnikov22a.html'
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
