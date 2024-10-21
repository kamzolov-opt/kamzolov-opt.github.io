---
title: 'A Damped Newton Method Achieves Global $O(\frac{1}{k^2})$ and Local Quadratic Convergence Rate'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Slavomír Hanzely
  - admin
  - Dmitry Pasechnyuk
  - Alexander Gasnikov
  - Peter Richtárik
  - Martin Takáč
  
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-10-31'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: "In *NeurIPS 2022: Advances in Neural Information Processing Systems 35*"
publication_short: "In *NeurIPS 2022*"

abstract: "In this paper, we present the first stepsize schedule for Newton method resulting in fast global and local convergence guarantees. In particular, we a) prove an $O(1/k^2)$ global rate, which matches the state-of-the-art global rate of cubically regularized Newton method of Polyak and Nesterov (2006) and of regularized Newton method of Mishchenko (2021), and the later variant of Doikov and Nesterov (2021), b) prove a local quadratic rate, which matches the best-known local rate of second-order methods, and c) our stepsize formula is simple, explicit, and does not require solving any subproblem. Our convergence proofs hold under affine-invariant assumptions closely related to the notion of self-concordance. Finally, our method has competitive performance when compared to existing baselines which share the same fast global convergence guarantees."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Second-Order Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:2211.00140
   url: https://arxiv.org/abs/2211.00140
   
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://proceedings.neurips.cc/paper_files/paper/2022/hash/a1f0c0cd6caaa4863af5f12608edf63e-Abstract-Conference.html'
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
