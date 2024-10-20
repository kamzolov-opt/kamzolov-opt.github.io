---
title: 'Stochastic Gradient Methods with Preconditioned Updates'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Abdurakhmon Sadiev
  - Aleksandr Beznosikov
  - Abdulla Jasem Almansoori
  - admin
  - Rachael Tappenden
  - Martin Takáč
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-06-01'
doi: '10.1007/s10957-023-02365-3'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Optimization Theory and Applications* 
publication_short: In *JOTA*

abstract: This work considers the non-convex finite-sum minimization problem. There are several algorithms for such problems, but existing methods often work poorly when the problem is badly scaled and/or ill-conditioned, and a primary goal of this work is to introduce methods that alleviate this issue. Thus, here we include a preconditioner based on Hutchinson’s approach to approximating the diagonal of the Hessian and couple it with several gradient-based methods to give new ‘scaled’ algorithms Scaled SARAH and Scaled L-SVRG. Theoretical complexity guarantees under smoothness assumptions are presented. We prove linear convergence when both smoothness and the PL-condition are assumed. Our adaptively scaled methods use approximate partial second-order curvature information and, therefore, can better mitigate the impact of badly scaled problems. This improved practical performance is demonstrated in the numerical experiments also presented in this work.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - First-Order Methods

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
url_source: 'https://link.springer.com/article/10.1007/s10957-023-02365-3'
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
