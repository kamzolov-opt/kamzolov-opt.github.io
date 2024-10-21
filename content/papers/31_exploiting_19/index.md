---
title: 'Exploiting Higher-Order Derivatives in Convex Optimization Methods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alexander Gasnikov
  - Pavel Dvurechensky
  - Artem Agafonov
  - Martin Takáč
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-08-28'
doi: '10.1007/978-3-030-54621-2_858-1'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['book']

# Publication name and optional abbreviated publication name.
publication: "In *Encyclopedia of Optimization*"
#publication_short: "In *MICCAI 2022*"

abstract: "Exploiting higher-order derivatives in convex optimization is known at least since 1970's. In each iteration higher-order (also called tensor) methods minimize a regularized Taylor expansion of the objective function, which leads to faster convergence rates if the corresponding higher-order derivative is Lipschitz-continuous. Recently a series of lower iteration complexity bounds for such methods were proved, and a gap between upper an lower complexity bounds was revealed. Moreover, it was shown that such methods can be implementable since the appropriately regularized Taylor expansion of a convex function is also convex and, thus, can be minimized in polynomial time. Only very recently an algorithm with optimal convergence rate 1/k(3p+1)/2 was proposed for minimizing convex functions with Lipschitz p-th derivative. For convex functions with Lipschitz third derivative, these developments allowed to propose a second-order method with convergence rate 1/k5, which is faster than the rate 1/k3.5 of existing second-order methods."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Second-Order Optimization

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:2208.13190
   url: https://arxiv.org/abs/2208.13190
   
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://link.springer.com/referenceworkentry/10.1007/978-3-030-54621-2_858-1'
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
