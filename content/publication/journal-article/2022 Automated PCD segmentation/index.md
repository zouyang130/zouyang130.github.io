---
title: "Automated semantic segmentation of bridge components from large-scale point clouds using a weighted superpoint graph"
authors:
- Xiaofei Yang
- Enrique del Rey Castillo
- admin
- Liam Wotherspoon
- Yi Tan
author_notes: []

date: "2022-08-04T00:00:00Z"
doi: "https://doi.org/10.1016/j.autcon.2022.104519"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Automation in Construction*"
publication_short: ""

abstract: Deep learning techniques have the potential to provide versatile solutions for automated semantic segmentation of bridge point clouds, but previous studies were limited to small-scale bridge point clouds and focused on limited bridge component categories due to training sample scarcity. Additionally, no prior work considered the intrinsic data imbalance problem in the bridge dataset, with the points unequally distributed between the various components. This paper presents a weighted superpoint graph (WSPG) method, where bridge point clouds were firstly clustered into hundreds of semantically homogeneous superpoints that were then classified into different bridge components using PointNet and Graph Neural Networks. The WSPG method can recognize components directly from large-scale bridge point clouds and alleviate the data imbalance by leveraging a novel loss function that assigns weights according to the number of points contained in different bridge components. The effectiveness of the method was validated on both a real-world dataset with 5 categories of bridge components and a synthetic dataset with 8 categories of bridge components. Experiment results on the real-world dataset showed that the WSPG model achieved the best performance on all overall evaluation metrics of overall accuracy (OA 99.43%), mean class accuracy (mAcc 98.75%) and mean Intersection over Union (mIoU 96.49%) compared to the existing cutting edge models such as PointNet, DGCNN and the original SPG. Additionally, the WSPG method also surpassed the cutting edge representatives in terms of mAcc and mIoU on the synthetic dataset, especially increasing the original SPG by 8.5% mAcc and 6.7% mIoU. The successful application of the proposed method will significantly improve upper-level tasks such as digital twining for existing bridges.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Point cloud segmentation
- Bridge inspection
- Digital twin
featured: false

# links:
# - name: ""
#   url: ""
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
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

