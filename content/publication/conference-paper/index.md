---
title: 'Statistical Shape Model of the Eustachian Tube for Understanding and Managing Eustachian Tube Dysfunction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ameen Amanian
  - Yuliang Xiao
  - admin
  - Deepa Galaiya
  - Russell H. Taylor
  - Mathias Unberath
  - Manish Sahu
  - Francis X. Creighton

# Author notes (optional)
author_notes: 
  - 'Equal contribution'
  - 'Equal contribution'
  

date: '2022-10-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['poster-conference']

# Publication name and optional abbreviated publication name.
publication: "*Conference on Machine Intelligence in Medical Imaging (Oral)*"
publication_short: ""

abstract: Obtaining automated, objective 3-dimensional (3D) models of the Eustachian tube (ET) and the internal carotid artery (ICA) from computed tomography (CT) scans could provide useful navigational and diagnostic information for ET pathologies and interventions. We aim to develop a deep learning (DL) pipeline to automatically segment the ET and ICA and use these segmentations to compute distances between these structures. From a database of 30 CT scans, 60 ET and ICA pairs were manually segmented and used to train an nnU-Net model, a DL segmentation framework. These segmentations were also used to develop a quantitative tool to capture the magnitude and location of the minimum distance point (MDP) between ET and ICA. Performance metrics for the nnU-Net automated segmentations were calculated via the average Hausdorff distance (AHD) and dice similarity coefficient (DSC). The AHD for the ET and ICA were 0.922 and 0.246 mm, respectively. Similarly, the DSC values for the ET and ICA were 0.578 and 0.884. The mean MDP from ET to ICA in the cartilaginous region was 2.6 mm (0.7-5.3 mm) and was located on average 1.9 mm caudal from the bony cartilaginous junction. This study describes the first end-to-end DL pipeline for automated ET and ICA segmentation and analyzes distances between these structures. In addition to helping to ensure the safe selection of patients for ET dilation, this method can facilitate large-scale studies exploring the relationship between ET pathologies and the 3D shape of the ET.

# Summary. An optional shortened abstract.
summary: 'Obtaining automated, objective 3-dimensional (3D) models of the Eustachian tube (ET) and the internal carotid artery (ICA) from computed tomography (CT) scans could provide useful navigational and diagnostic information for ET pathologies and interventions. We aim to develop a deep learning (DL) pipeline to automatically segment the ET and ICA and use these segmentations to compute distances between these structures.'

tags:
  - Deep Learning, Eustachian Tube Dysfunction, Medical Imaging

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/conference-paper.pdf'
url_code: ''
url_dataset: ''
url_poster: '/CMIMI_Poster.pdf'
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


