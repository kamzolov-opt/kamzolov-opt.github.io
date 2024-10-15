---
title: 'Efficient Numerical Methods to Solve Sparse Linear Equations with Application to PageRank'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Anton Anikin
  - Alexander Gasnikov
  - Alexander Gornov
  - admin
  - Yury Maximov
  - Yurii Nesterov
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2015-08-30'
doi: '10.1080/10556788.2020.1858297'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Optimization Methods and Software* 
#publication_short: In *OMS*

abstract: Over the last two decades, the PageRank problem has received increased interest from the academic community as an efficient tool to estimate web-page importance in information retrieval. Despite numerous developments, the design of efficient optimization algorithms for the PageRank problem is still a challenge. This paper proposes three new algorithms with a linear time complexity for solving the problem over a bounded-degree graph. The idea behind them is to set up the PageRank as a convex minimization problem over a unit simplex, and then solve it using iterative methods with small iteration complexity. Our theoretical results are supported by an extensive empirical justification using real-world and simulated data.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Universal Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:1508.07607
   url: https://arxiv.org/abs/1508.07607
   
url_pdf: 'https://doi.org/10.1080/10556788.2020.1858297'
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
