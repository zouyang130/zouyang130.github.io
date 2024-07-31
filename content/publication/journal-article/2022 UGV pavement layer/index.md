---
title: "Effective Motion Sensors and Deep Learning Techniques for Unmanned Ground Vehicle (UGV)-Based Automated Pavement Layer Change Detection in Road Construction"
authors:
- Tirth Patel
- Brian H. W. Guo
- Jacobus Daniel van der Walt
- admin
author_notes: []

date: "2022-12-20T00:00:00Z"
doi: " https://doi.org/10.3390/buildings13010005"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Buildings*"
publication_short: ""

abstract: 'As-built progress of the constructed pavement should be monitored effectively to provide prompt project control. However, current pavement construction progress monitoring practices (e.g., data collection, processing, and analysis) are typically manual, time-consuming, tedious, and error-prone. To address this, this study proposes sensors mounted using a UGV-based methodology to develop a pavement layer change classifier measuring pavement construction progress automatically. Initially, data were collected using the UGV equipped with a laser ToF (time-of-flight) distance sensor, accelerometer, gyroscope, and GPS sensor in a controlled environment by constructing various scenarios of pavement layer change. Subsequently, four Long Short-Term Memory network variants (LSTMs) (LSTM, BiLSTM, CNN-LSTM, and ConvLSTM) were implemented on collected sensor data combinations for developing pavement layer change classifiers. The authors conducted the experiment to select the best sensor combinations for feature detection of the layer change classifier model. Subsequently, individual performance measures of each class with learning curves and confusion matrices were generated using sensor combination data to find out the best algorithm among all implemented algorithms. The experimental result demonstrates the (az + gx + D) sensor combination as the best feature detector with high-performance measures (accuracy, precision, recall, and F1 score). The result also confirms the ConvLSTM as the best algorithm with the highest overall accuracy of 97.88% with (az + gx + D) sensor combination data. The high-performance measures with the proposed approach confirm the feasibility of detecting pavement layer changes in real pavement construction projects. This proposed approach can potentially improve the efficiency of road construction progress measurement. This research study is a stepping stone for automated road construction progress monitoring.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Deep learning
- Pavement construction
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

