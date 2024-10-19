---
title: 'Embedded Online Machine Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nikita Yudin
  - admin
  - Vadim Sinolits
  - Pavel Golovkin
  - Alexey Erchenko
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-11-24'
doi: '10.1109/EnT50460.2021.9681738'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: In *2021 International Conference Engineering and Telecommunication (En\&T)* 
#publication_short: In *OMS*

abstract: The paper presents research on a set of “classical” machine learning algorithms for tiny (microbatch, i.e., batch size equal to or less than 128) embedded online machine learning on ARM processor boards with hard memory limits and a tiny memory footprint while running on a single CPU without multithreading. We propose mathematical improvements to algorithms as well as other programming optimizations. In the presence of evolving data streams, we present an adaptation of the Gradient Boosting Decision Trees (GBDT) learning algorithm for classification tasks, the eXtreme Gradient Boosting (XGBoost, XGB) and the Random Forest (RF) learning algorithms for supervised anomaly detection tasks, and the Extended Isolation Forest (EIF) learning algorithm for unsupervised anomaly detection tasks. In this scenario, as new data is added over time, the connection between the class and the characteristics may shift, resulting in concept drift. The proposed technique generates new members of the ensemble from microbatches and/or batches of data for each algorithm as new data becomes available. The maximum ensemble size is specified, but learning does not stop when it reaches this size because the ensemble is constantly updated with new data to ensure compatibility with the current notion. We tested our technique on real-world data and compared it to the original batch-incremental learning algorithms for data streams. Our implementations gain a speedup in inference up to several times even demonstrating prediction quality improvement by 0.1-0.3 in terms of F1 measure in some cases.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Applications

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
url_source: 'https://ieeexplore.ieee.org/document/9681738'
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
