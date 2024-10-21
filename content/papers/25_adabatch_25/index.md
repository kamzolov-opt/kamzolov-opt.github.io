---
title: 'AdaBatchGrad: Combining Adaptive Batch Size and Adaptive Step Size'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Petr Ostroukhov
  - Aigerim Zhumabayeva
  - Chulu Xiang
  - Alexander Gasnikov
  - Martin Takáč
  - admin
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-02-07'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: "*Preprint, Under Review*"
#publication_short: In *OMS*

abstract: "This paper presents a novel adaptation of the Stochastic Gradient Descent (SGD), termed AdaBatchGrad. This modification seamlessly integrates an adaptive step size with an adjustable batch size. An increase in batch size and a decrease in step size are well-known techniques to tighten the area of convergence of SGD and decrease its variance. A range of studies by R. Byrd and J. Nocedal introduced various testing techniques to assess the quality of mini-batch gradient approximations and choose the appropriate batch sizes at every step. Methods that utilized exact tests were observed to converge within - iterations. Conversely, inexact test implementations sometimes resulted in non-convergence and erratic performance. To address these challenges, AdaBatchGrad incorporates both adaptive batch and step sizes, enhancing the method's robustness and stability. For exact tests, our approach converges in - iterations, analogous to standard gradient descent. For inexact tests, it achieves convergence in - iterations. This makes AdaBatchGrad markedly more robust and computationally efficient relative to prevailing methods. To substantiate the efficacy of our method, we experimentally show, how the introduction of adaptive step size and adaptive batch size gradually improves the performance of regular SGD. The results imply that AdaBatchGrad surpasses alternative methods, especially when applied to inexact tests."
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Adaptive Methods

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:2402.05264
   url: https://arxiv.org/abs/2402.05264
   
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
