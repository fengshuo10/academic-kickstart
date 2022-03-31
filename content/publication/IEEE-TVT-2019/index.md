---
title: "A Cooperative Driving Strategy for Merging at On-Ramps Based on Dynamic Programming"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Huaxin Pei
- Shuo Feng *
- Yi Zhang
- Danya Yao

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2019-10-14T00:00:00Z"
doi: "10.1109/TVT.2019.2947192"

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-02-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Vehicular Technology*
publication_short: In *IEEE Transactions on Vehicular Technology*

abstract: Cooperative driving emerges as a promising way to improve efficiency and safety for Connected and Automated Vehicles (CAVs). Its key idea is to design a strategy to schedule the movements of neighboring vehicles. The typical cooperative driving strategies can be categorized into two categories. The first category is optimal strategy, which aims to find the globally optimal passing order of vehicles, but the computational cost of this strategy grows significantly with the increasing number of vehicles. The second category is sub-optimal strategy, which uses heuristic rules or other methods to export an acceptable local optimal solution within a limited computation time. However, there usually lacks a rigorous theoretical guarantee of the performances, and further validation is always required for practical applications. To overcome all these limitations, a computationally efficient strategy is proposed to obtain the globally optimal passing order based on dynamic programming (DP). Specifically, the problem of merging at on-ramps is resolved by a DP method, which uses the domain knowledge to reduce the complexity by well defining the state space, state transition, and criterion function. With the DP method, it is proved that the globally optimal passing order can be obtained with the quadratic polynomial computational complexity of O(N^2), where N denotes the number of vehicles. Simulation results demonstrate the performances of the proposed strategy regarding optimality and efficiency.


# Summary. An optional shortened abstract.
summary: A computationally efficient strategy is proposed to obtain the globally optimal passing order based on dynamic programming (DP). Specifically, the problem of merging at on-ramps is resolved by a DP method, which uses the domain knowledge to reduce the complexity by well defining the state space, state transition, and criterion function. With the DP method, it is proved that the globally optimal passing order can be obtained with the quadratic polynomial computational complexity of O(N^2), where N denotes the number of vehicles. 



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

