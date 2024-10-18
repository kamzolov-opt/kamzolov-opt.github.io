---
title: 'On the Optimal Combination of Tensor Optimization Methods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alexander Gasnikov
  - Pavel Dvurechensky
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-02-03'
doi: '10.1007/978-3-030-62867-3_13'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "In *Lecture Notes in Computer Science*"
#publication_short: In *LNCS*

abstract: We consider the minimization problem of a sum of a number of functions having Lipshitz p-th order derivatives with different Lipschitz constants. In this case, to accelerate optimization, we propose a general framework allowing to obtain near-optimal oracle complexity for each function in the sum separately, meaning, in particular, that the oracle for a function with lower Lipschitz constant is called a smaller number of times. As a building block, we extend the current theory of tensor methods and show how to generalize near-optimal tensor methods to work with inexact tensor step. Further, we investigate the situation when the functions in the sum have Lipschitz derivatives of a different order. For this situation, we propose a generic way to separate the oracle complexity between the parts of the sum. Our method is not optimal, which leads to an open problem of the optimal combination of oracles of a different order.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Second-Order Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:2002.01004
   url: https://arxiv.org/abs/2002.01004
   
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://link.springer.com/chapter/10.1007/978-3-030-62867-3_13'
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
