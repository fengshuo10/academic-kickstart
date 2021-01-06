---
title: "Traffic flow data compression considering burst components"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Shuo Feng
- Ruimin Ke
- Xingmin Wang
- Yi Zhang
- Li Li

# Author notes (optional)
# author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2017-11-01T00:00:00Z"
doi: "10.1049/iet-its.2016.0328"

# Schedule page publish date (NOT publication's date).
# publishDate: "2020-02-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IET Intelligent Transport Systems*
publication_short: In *IET Intelligent Transport Systems*

abstract: Many recent applications of intelligent transportation systems require both real-time and network-wide traffic flow data as input. However, as the detection time and network size increase, the data volume may become very large in terms of both dimension and scale. To address this concern, various traffic flow data compression methods have been proposed, which archive the low-dimensional subspace rather than the original data. Many studies have shown the traffic flow data consist of different components, i.e. low-dimensional intra-day trend, Gaussian type fluctuation and burst components. Existing compression methods cannot compress the burst components well and provide very limited choices of compression ratio (CR). A better compression method should have the ability to archive all the dominant information in different components of traffic flow data. In this study, the authors compare the influence of different data reformatting, archive the bursts defined before in descending order with respect to the absolute value of the burst points and propose a flexible compression framework to balance between burst components and low-dimensional intra-day trend. Experimental results show that the proposed framework promotes the reconstruction accuracy significantly. Moreover, the proposed framework provides more flexible choices with respect to CR, which can benefit a variety of applications.



# Summary. An optional shortened abstract.
summary: In this study, the authors compare the influence of different data reformatting, archive the bursts defined before in descending order with respect to the absolute value of the burst points and propose a flexible compression framework to balance between burst components and low-dimensional intra-day trend.


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

