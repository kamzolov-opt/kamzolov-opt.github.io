---
title: 'Suppressing Poisoning Attacks on Federated Learning for Medical Imaging'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Naif Alkhunaizi
  - admin
  - Martin Takáč
  - Karthik Nandakumar
  
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-07-15'
doi: '10.1007/978-3-031-16452-1_64'

# Schedule page publish date (NOT publication's date).
#publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: "In *MICCAI 2022: Conference on Medical Image Computing and Computer Assisted Intervention 2022*"
publication_short: "In *MICCAI 2022*"

abstract: "Collaboration among multiple data-owning entities (e.g., hospitals) can accelerate the training process and yield better machine learning models due to the availability and diversity of data. However, privacy concerns make it challenging to exchange data while preserving confidentiality. Federated Learning (FL) is a promising solution that enables collaborative training through exchange of model parameters instead of raw data. However, most existing FL solutions work under the assumption that participating clients are \emph{honest} and thus can fail against poisoning attacks from malicious parties, whose goal is to deteriorate the global model performance. In this work, we propose a robust aggregation rule called Distance-based Outlier Suppression (DOS) that is resilient to byzantine failures. The proposed method computes the distance between local parameter updates of different clients and obtains an outlier score for each client using Copula-based Outlier Detection (COPOD). The resulting outlier scores are converted into normalized weights using a softmax function, and a weighted average of the local parameters is used for updating the global model. DOS aggregation can effectively suppress parameter updates from malicious clients without the need for any hyperparameter selection, even when the data distributions are heterogeneous. Evaluation on two medical imaging datasets (CheXpert and HAM10000) demonstrates the higher robustness of DOS method against a variety of poisoning attacks in comparison to other state-of-the-art methods. The code can be found here."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Distributed Optimization

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: arXiv:2207.10804
   url: https://arxiv.org/abs/2207.10804
   
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://link.springer.com/chapter/10.1007/978-3-031-16452-1_64'
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
