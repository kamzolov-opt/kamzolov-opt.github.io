---
title: 'Universal Intermediate Gradient Method for Convex Problems with Inexact Oracle'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Pavel Dvurechensky
  - Alexander Gasnikov
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2017-12-17'
doi: '10.1080/10556788.2019.1711079'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Optimization Methods and Software* 
#publication_short: In *OMS*

abstract: In this paper, we propose new first-order methods for minimization of a convex function on a simple convex set. We assume that the objective function is a composite function given as a sum of a simple convex function and a convex function with inexact Hölder-continuous subgradient. We propose Universal Intermediate Gradient Method. Our method enjoys both the universality and intermediateness properties. Following the ideas of Nesterov (Math. Program. 152 (2015), pp. 381–404) on Universal Gradient Methods, our method does not require any information about the Hölder parameter and constant and adjusts itself automatically to the local level of smoothness. On the other hand, in the spirit of the Intermediate Gradient Method proposed by Devolder et al. (CORE Discussion Paper 2013/17, 2013), our method is intermediate in the sense that it interpolates between Universal Gradient Method and Universal Fast Gradient Method. This allows to balance the rate of convergence of the method and rate of the oracle error accumulation. Under the additional assumption of strong convexity of the objective, we show how the restart technique can be used to obtain an algorithm with faster rate of convergence.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Universal Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:1712.06036
   url: https://arxiv.org/abs/1712.06036
   
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.tandfonline.com/doi/full/10.1080/10556788.2019.1711079'
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
