---
title: 'An Accelerated Second-Order Method for Distributed Stochastic Optimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Artem Agafonov
  - Pavel Dvurechensky
  - Gesualdo Scutari
  - Alexander Gasnikov
  - admin
  - Alexander Lukashevich
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-03-26'
doi: '10.1109/CDC45484.2021.9683400'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: In *2021 60th IEEE Conference on Decision and Control (CDC)* 
#publication_short: In *OMS*

abstract: We consider centralized distributed algorithms for general stochastic convex optimization problems which we approximate by a finite-sum minimization problem with summands distributed among computational nodes. We exploit statistical similarity between the summands and the whole sum to construct a distributed accelerated cubic-regularized Newton’s method that achieves lower communication complexity bound for this setting and improves upon existing upper bound. Further, we use this algorithm to obtain convergence rate bounds for the original stochastic optimization problem and compare our bounds with the existing ones in several regimes when the goal is to minimize the number of communication rounds and improve the parallelization when increasing the number of workers.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Distributed Optimization
  - Second-Order Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:2103.14392
   url: https://arxiv.org/abs/2103.14392
   
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/9683400'
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
