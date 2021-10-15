---
title: "Corner Case Generation and Analysis for Safety Assessment of Autonomous Vehicles"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Haowei Sun
- Shuo Feng*
- Xintao Yan
- Henry X. Liu

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-07-02T00:00:00Z"
doi: "10.1177/03611981211018697"

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

abstract:Testing and evaluation is a crucial step in the development and deployment of connected and automated vehicles (CAVs). To comprehensively evaluate the performance of CAVs, it is necessary to test the CAVs in safety-critical scenarios, which rarely happen in a naturalistic driving environment. Therefore, how to purposely and systematically generate these corner cases becomes an important problem. Most existing studies focus on generating adversarial examples for perception systems of CAVs, whereas limited efforts have been put into decision-making systems, which is the highlight of this paper. As the CAVs need to interact with numerous background vehicles (BVs) for a long duration, variables that define the corner cases are usually high-dimensional, which makes the generation a challenging problem. In this paper, a unified framework is proposed to generate corner cases for decision-making systems. To address the challenge brought by high dimensionality, the driving environment is formulated based on the Markov decision process, and the deep reinforcement learning techniques are applied to learn the behavior policy of BVs. With the learned policy, BVs behave and interact with the CAVs more aggressively, resulting in more corner cases. To further analyze the generated corner cases, the techniques of feature extraction and clustering are utilized. By selecting representative cases of each cluster and outliers, the valuable corner cases can be identified from all generated corner cases. Simulation results of a highway driving environment show that the proposed methods can effectively generate and identify the valuable corner cases.




# Summary. An optional shortened abstract.
summary: In this paper, a unified framework is proposed to generate corner cases for decision-making systems. To address the challenge brought by high dimensionality, the driving environment is formulated based on the Markov decision process, and the deep reinforcement learning techniques are applied to learn the behavior policy of BVs. With the learned policy, BVs behave and interact with the CAVs more aggressively, resulting in more corner cases.


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

