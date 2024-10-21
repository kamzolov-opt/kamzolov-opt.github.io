---
title: 'Accelerated Adaptive Cubic Regularized Quasi-Newton Methods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Klea Ziu
  - Artem Agafonov
  - Martin Takáč
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-02-10'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: "*Preprint, Under Review*"
#publication_short: "In *MICCAI 2022*"

abstract: "In this paper, we propose the first Quasi-Newton method with a global convergence rate of $O(k^{−1})$ for general convex functions. Quasi-Newton methods, such as BFGS, SR-1, are well-known for their impressive practical performance. However, they may be slower than gradient descent for general convex functions, with the best theoretical rate of $O(k^{−1/3})$. This gap between impressive practical performance and poor theoretical guarantees was an open question for a long period of time. In this paper, we make a significant step to close this gap. We improve upon the existing rate and propose the Cubic Regularized Quasi-Newton Method with a convergence rate of $O(k^{−1})$. The key to achieving this improvement is to use the Cubic Regularized Newton Method over the Damped Newton Method as an outer method, where the Quasi-Newton update is an inexact Hessian approximation. Using this approach, we propose the first Accelerated Quasi-Newton method with a global convergence rate of O(k−2) for general convex functions. In special cases where we can improve the precision of the approximation, we achieve a global convergence rate of $O(k^{−3})$, which is faster than any first-order method. To make these methods practical, we introduce the Adaptive Inexact Cubic Regularized Newton Method and its accelerated version, which provide real-time control of the approximation error. We show that the proposed methods have impressive practical performance and outperform both first and second-order methods."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Quasi-Newton Methods
  - Second-Order Methods

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: arXiv:2302.04987
   url: https://arxiv.org/abs/2302.04987
   
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
