---
title: "Tube-Based Discrete Controller Design for Vehicle Platoons Subject to Disturbances and Saturation Constraints"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Shuo Feng
- Haowei Sun
- Yi Zhang
- Jianfeng Zheng
- Henry X. Liu
- Li Li

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2019-02-18T00:00:00Z"
doi: "10.1109/TCST.2019.2896539"

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-02-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Control Systems Technology*
publication_short: In *IEEE Transactions on Control Systems Technology*

abstract: Cooperative adaptive cruise control (CACC) is a promising intelligent vehicle technology for improving traffic flow stability, throughput, and safety. One major control objective of CACC is to guarantee L p string stability, i.e., L p -norm measured disturbance is uniformly bounded along the vehicle string. Most existing methods for string stability are laborious for implementation without considering either heterogeneous disturbances (e.g., tracking errors and unmodeled dynamics) or saturation constraints (e.g., input saturation). The decentralized model predictive control (MPC) method, which is a widely used feedforward control for string stability, suffers the burdens of computation cost and intervehicular communication. To fill these gaps, we distinguish different types of disturbances and use different ways to handle them. We use feedforward control for large yet infrequent disturbances and feedback control for small yet frequent disturbances. Different from MPC, our feedforward control is event-triggered so that the intervehicle communication and planning costs can be significantly reduced. Different from pure robust feedback control, our combination of feedback and feedforward control could reduce the conservation of the controller. Theoretical analysis and simulations show that the proposed method guarantees L p string stability of vehicle platoons considering heterogeneous disturbances and saturation constraints.

# Summary. An optional shortened abstract.
summary: Most existing methods for string stability are laborious for implementation without considering either heterogeneous disturbances (e.g., tracking errors and unmodeled dynamics) or saturation constraints (e.g., input saturation). We use feedforward control for large yet infrequent disturbances and feedback control for small yet frequent disturbances. Different from MPC, our feedforward control is event-triggered so that the intervehicle communication and planning costs can be significantly reduced. Different from pure robust feedback control, our combination of feedback and feedforward control could reduce the conservation of the controller.

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

