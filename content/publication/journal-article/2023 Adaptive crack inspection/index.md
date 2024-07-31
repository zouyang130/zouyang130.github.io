---
title: "An adaptive crack inspection method for building surface based on BIM, UAV and edge computing"
authors:
- Yi Tan
- Wen Yi
- Penglu Chen
- admin
author_notes: []

date: "2023-11-03T00:00:00Z"
doi: "https://doi.org/10.1016/j.autcon.2023.105161"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Automation in Construction*"
publication_short: ""

abstract: Unmanned aerial vehicle (UAV) and building information modeling (BIM) have been applied to inspect building surfaces to improve efficiency and reduce labor costs. However, most of the current research focus on the inspection mode of “first collect and then identify” with limited intelligence. Therefore, this study proposes a “global-local” adaptive inspection method for building surfaces by integrating BIM, UAV (with multifunction camera), and edge computing, enabling real-time synchronization of crack data collection and analysis. First, the building surface area to be inspected is extracted from BIM to generate global inspection points using the selected camera's field of view (FOV) and considering coordinates transformation between BIM and reality. Then, A star algorithm integrating with genetic algorithm (GA) is used to optimize the global flight path based on generated inspection points. Finally, the coordinates of the inspection points based on BIM are converted into real-world coordinates, and the flight parameters such as the flight yaw angle (FYA) and the gimbal yaw angle (GYA) are calculated to generate the inspection mission. During global inspection, a local adaptive inspection is proposed for each FOV through real-time local crack identification and flight replanning using edge computing and zoom camera. In addition, multiple battery supply points are automatically added considering the endurance of the UAV. A real building has been used to validate the proposed “global-local” adaptive inspection method. The experiment results show that the inspection time has been significantly reduced compared with the traditional method, and the crack identification of building surfaces can be implemented with high efficiency, precision, quality, and low cost.

# Summary. An optional shortened abstract.
summary: ''

tags:
- UAV
- Building inspection
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

