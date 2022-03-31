---
title: "Robust Platoon Control in Mixed Traffic Flow Based on Tube Model Predictive Control"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Shuo Feng
- Ziyou Song
- Zhaojian Li
- Yi Zhang
- Li Li

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-02-19T00:00:00Z"
doi: "10.1109/TIV.2021.3060626"

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-02-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Intelligent Vehicles*
publication_short: In *IEEE Transactions on Intelligent Vehicles*

abstract: The design of cooperative adaptive cruise control is critical in mixed traffic flow, where connected and automated vehicles (CAVs) and human-driven vehicles (HDVs) coexist. Compared with pure CAVs, the major challenge is how to handle the prediction uncertainty of HDVs, which can cause significant state deviation of CAVs from planned trajectories. In most existing studies, model predictive control (MPC) is utilized to replan CAVs' trajectories to mitigate the deviation at each time step. However, as the replanning process is usually conducted by solving an optimization problem with information through inter-vehicular communication, MPC methods suffer from heavy computational and communicational burdens. To address this limitation, a robust platoon control framework is proposed based on tube MPC in this paper. The prediction uncertainty is dynamically mitigated by the feedback control and restricted inside a set with a high probability. When the uncertainty exceeds the set or additional external disturbance emerges, the feedforward control is triggered to plan a "tube'' (a sequence of sets), which can bound CAVs' actual trajectories. As the replanning process is usually not required, the proposed method is much more efficient regarding computation and communication, compared with the MPC method. Comprehensive simulations are provided to validate the effectiveness of the proposed framework.


# Summary. An optional shortened abstract.
summary: A robust platoon control framework is proposed for mixed traffic flow where connected and automated vehicles (CAVs) and human-driven vehicles (HDVs) coexist. The prediction uncertainty is dynamically mitigated by the feedback control and restricted inside a set with a high probability. When the uncertainty exceeds the set or additional external disturbance emerges, the feedforward control is triggered to plan a "tube" (a sequence of sets), which can bound CAVs' actual trajectories. As the replanning process is usually not required, the proposed method is much more efficient regarding computation and communication, compared with the MPC method.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

