---
title: 'Hyperfast Second-Order Local Solvers for Efficient Statistically Preconditioned Distributed Optimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Pavel Dvurechensky
  - admin
  - Alexander Lukashevich
  - Soomin Lee
  - Erik Ordentlich
  - César A. Uribe
  - Alexander Gasnikov
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-02-16'
doi: '10.1016/j.ejco.2022.100045'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *EURO Journal on Computational Optimization* 
#publication_short: In *OMS*

abstract: Statistical preconditioning enables fast methods for distributed large-scale empirical risk minimization problems. In this approach, multiple worker nodes compute gradients in parallel, which are then used by the central node to update the parameter by solving an auxiliary (preconditioned) smaller-scale optimization problem. The recently proposed Statistically Preconditioned Accelerated Gradient (SPAG) method [1] has complexity bounds superior to other such algorithms but requires an exact solution for computationally intensive auxiliary optimization problems at every iteration. In this paper, we propose an Inexact SPAG (InSPAG) and explicitly characterize the accuracy by which the corresponding auxiliary subproblem needs to be solved to guarantee the same convergence rate as the exact method. We build our results by first developing an inexact adaptive accelerated Bregman proximal gradient method for general optimization problems under relative smoothness and strong convexity assumptions, which may be of independent interest. Moreover, we explore the properties of the auxiliary problem in the InSPAG algorithm assuming Lipschitz third-order derivatives and strong convexity. For such problem class, we develop a linearly convergent Hyperfast second-order method and estimate the total complexity of the InSPAG method with hyperfast auxiliary problem solver. Finally, we illustrate the proposed method's practical efficiency by performing large-scale numerical experiments on logistic regression models. To the best of our knowledge, these are the first empirical results on implementing high-order methods on large-scale problems, as we work with data where the dimension is of the order of 3 million, and the number of samples is 700 million.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Second-Order Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:2102.08246
   url: https://arxiv.org/abs/2102.08246
   
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.sciencedirect.com/science/article/pii/S2192440622000211?'
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
