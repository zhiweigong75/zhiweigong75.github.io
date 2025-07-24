---
title: 'Evaluating the Generalizability of Video-based Assessment of Intraoperative Surgical Skill in Capsulorhexis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Bohua Wan
  - Jay N. Paranjape
  - Shameema Sikder
  - Vishal M. Patel
  - S. Swaroop Vedula

# Author notes (optional)
author_notes: 
  - 'Equal contribution'
  - 'Equal contribution'
  

date: '2025-05-22T00:00:00Z'
doi: '10.1007/s11548-025-03406-0'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal of Computer Assisted Radiology and Surgery*"
publication_short: ""

abstract: Assessment of intraoperative surgical skill is necessary to train surgeons and certify them for practice. The generalizability of deep learning models for video-based assessment (VBA) of surgical skill has not yet been evaluated. In this work, we evaluated one unsupervised domain adaptation (UDA) and three semi-supervised (SSDA) methods for generalizability of models for VBA of surgical skill in capsulorhexis by training on one dataset and testing on another. We used two datasets, D99 and Cataract-101 (publicly available), and two state-of-the-art models for capsulorhexis. The models include a convolutional neural network (CNN) to extract features from video images, followed by a long short-term memory (LSTM) network or a transformer. We augmented the CNN and the LSTM with attention modules. We estimated accuracy, sensitivity, specificity, and area under the receiver operating characteristic curve (AUC). Maximum mean discrepancy (MMD) did not improve generalizability of CNN-LSTM but slightly improved CNN transformer. Among the SSDA methods, Group Distributionally Robust Supervised Learning improved generalizability in most cases. Model performance improved with the domain adaptation methods we evaluated, but it fell short of within-dataset performance. Our results provide benchmarks on a public dataset for others to compare their methods.

# Summary. An optional shortened abstract.
summary: ''

tags:
  - Cataract surgery, Domain adaptation, Surgical skill assessment, Transformer.

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/IJCARS-paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---


