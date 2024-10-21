---
title: 'Exploring Jacobian Inexactness in Second-Order Methods for Variational Inequalities: Lower Bounds, Optimal Algorithms and Quasi-Newton Approximations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Artem Agafonov
  - Petr Ostroukhov
  - Roman Mozhaev
  - Konstantin Yakovlev
  - Eduard Gorbunov
  - Martin Takáč
  - Alexander Gasnikov
  - admin
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-05-25'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: "In *NeurIPS 2024: Advances in Neural Information Processing Systems 37 (Spotlight)*"
publication_short: "In *NeurIPS 2024 (Spotlight)*"

abstract: "Variational inequalities represent a broad class of problems, including minimization and min-max problems, commonly found in machine learning. Existing second-order and high-order methods for variational inequalities require precise computation of derivatives, often resulting in prohibitively high iteration costs. In this work, we study the impact of Jacobian inaccuracy on second-order methods. For the smooth and monotone case, we establish a lower bound with explicit dependence on the level of Jacobian inaccuracy and propose an optimal algorithm for this key setting. When derivatives are exact, our method converges at the same rate as exact optimal second-order methods. To reduce the cost of solving the auxiliary problem, which arises in all high-order methods with global convergence, we introduce several Quasi-Newton approximations. Our method with Quasi-Newton updates achieves a global sublinear convergence rate. We extend our approach with a tensor generalization for inexact high-order derivatives and support the theory with experiments."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Quasi-Newton Methods
  - Second-Order Methods

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: arXiv:2405.15990
   url: https://arxiv.org/abs/2405.15990
   
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
