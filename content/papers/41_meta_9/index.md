---
title: 'Near-Optimal Hyperfast Second-Order Method for Convex Optimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-02-20'
doi: '10.1007/978-3-030-58657-7_15'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "In *Lecture Notes in Computer Science*"
#publication_short: In *LNCS*

abstract: In this paper, we present a new Hyperfast Second-Order Method with convergence rate $O(N^\{-5\})$ up to a logarithmic factor for the convex function with Lipschitz 3rd derivative. This method based on two ideas. The first comes from the superfast second-order scheme of Yu. Nesterov (CORE Discussion Paper 2020/07, 2020). It allows implementing the third-order scheme by solving subproblem using only the second-order oracle. This method converges with rate $O(N^\{-4\})$. The second idea comes from the work of Kamzolov et al. (arXiv:2002.01004). It is the inexact near-optimal third-order method. In this work, we improve its convergence and merge it with the scheme of solving subproblem using only the second-order oracle. As a result, we get convergence rate $O(N^\{-5\})$ up to a logarithmic factor. This convergence rate is near-optimal and the best known up to this moment.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Second-Order Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:2002.09050
   url: https://arxiv.org/abs/2002.09050
   
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://link.springer.com/chapter/10.1007/978-3-030-58657-7_15'
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
