---
title: "Learning-Based Stochastic Driving Model for Autonomous Vehicle Testing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Lin Liu
- Shuo Feng
- Yiheng Feng
- Xichan Zhu
- Henry X. Liu

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-08-13T00:00:00Z"
doi: "10.1177/03611981211035756"

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-02-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Transportation Research Record*
publication_short: In *Transportation Research Record*

abstract: In the simulation-based testing and evaluation of autonomous vehicles (AVs), how background vehicles (BVs) drive directly influences the AV’s driving behavior and further affects the test results. Most existing simulation platforms use either predetermined trajectories or deterministic driving models to model BV behaviors. However, predetermined BV trajectories cannot react to AV maneuvers, and deterministic models are different from real human drivers because of the lack of stochastic components and errors. Both methods lead to unrealistic traffic scenarios. This paper presents a learning-based stochastic driving model that meets the unique needs of AV testing (i.e., interactive and human-like stochasticity). The model is built based on the long short-term memory architecture. By incorporating the concept of quantile regression into the loss function of the model, the stochastic behaviors are reproduced without prior assumption of human drivers. The model is trained with the large-scale naturalistic driving data (NDD) from the Safety Pilot Model Deployment project and compared with a stochastic intelligent driving model (IDM). Analysis of individual trajectories shows that the proposed model can reproduce more similar trajectories of human drivers than IDM. To validate the ability of the proposed model in generating a naturalistic driving environment, traffic simulation experiments are implemented. The results show that traffic flow parameters such as speed, range, and time headway distribution match closely with the NDD, which is of significant importance for AV testing and evaluation.




# Summary. An optional shortened abstract.
summary: This paper presents a learning-based stochastic driving model that meets the unique needs of AV testing (i.e., interactive and human-like stochasticity). The model is built based on the long short-term memory architecture. By incorporating the concept of quantile regression into the loss function of the model, the stochastic behaviors are reproduced without prior assumption of human drivers.


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

