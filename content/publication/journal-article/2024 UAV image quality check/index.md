---
title: "Rapid in-flight image quality check for UAV-enabled bridge inspection"
authors:
- Feng Wang
- admin
- Xiaoyu Chen
- Cheng Zhang
- Lei Hou
- Enrique del Rey Castillo
- James B.P. Lim
author_notes: []

date: "2024-05-13T00:00:00Z"
doi: "https://doi.org/10.1016/j.isprsjprs.2024.05.008"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*ISPRS Journal of Photogrammetry and Remote Sensing*"
publication_short: ""

abstract: Combining Unmanned Aerial Vehicles (UAVs) and close-range photogrammetry has become a safer, more efficient, and cost-effective solution for bridge inspection compared to conventional methods. However, close-range bridge images captured by UAVs often suffer from severe quality issues, such as blurriness, improper exposure, limited coverage, or insufficient resolution. These issues can adversely affect subsequent damage identification and bridge condition assessment, thereby hindering the widespread application of UAVs in bridge inspection. This paper presents a novel in-flight image quality check (IIQC) framework for rapidly assessing UAV-captured images against bridge inspection requirements. This framework incorporates (1) a new coarse-to-fine image pose estimation approach for precisely estimating the relative poses of UAV images with respect to a reference model, (2) a comprehensive set of refined image quality metrics for assessing image quality across various aspects, and (3) an Image Quality Metrics (IQM)-embedded bridge representation model for visualising the evaluation results. All components within this framework have been validated through extensive simulation and real-world experiments, encompassing various bridge structures (i.e., girder, arch, and truss bridges) and different weather conditions. The results show that (1) the average root mean square error (RMSE) of the estimated image poses by the coarse-to-fine method across multiple structures reached 0.189 m in position and 0.203° in orientation, showcasing an improvement over 50 % than the image poses retrieved from the UAV; (2) the image quality metrics offer comprehensive insights into image blurriness probability and exposure intensity at the pixel level and can effectively identifying missing and insufficient captured areas; (3) the bridge representation model is capable of delivering valuable and user-friendly feedback of the assessment results to the pilot; (4) the IIQC framework can offer a rapid and comprehensive assessment of close-range UAV images in near real-time by leveraging an existing Building Information Model (BIM) of the target bridge, serving as a novel and efficient solution to thoroughly tackle image quality issues in UAV-enabled bridge inspection. Its versatility can potentially be extended to encompass other structural types, including buildings and dams.

# Summary. An optional shortened abstract.
summary: ''

tags:
- UAV
- Bridge inspection
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

