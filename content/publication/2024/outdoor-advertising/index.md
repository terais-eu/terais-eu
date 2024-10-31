---
title: "Evaluating the Significance of Outdoor Advertising from Driver’s Perspective Using Computer Vision"
authors:
  - Zuzana Černeková
  - Zuzana Berger Haladová
  - Ján Špirka
  - Viktor Kocur
date: '2023-11-10T00:00:00Z'
doi: '10.1109/DISA59116.2023.10308914'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '2023 World Symposium on Digital Intelligence for Systems and Machines'
publication_short: 'DISA'

abstract: |
  Outdoor advertising, such as roadside billboards, plays a significant role in marketing campaigns but can also be a
  distraction for drivers, potentially leading to accidents. In this study, we propose a pipeline for evaluating the
  significance of roadside billboards in videos captured from a driver’s perspective. We have collected and annotated a
  new BillboardLamac dataset, comprising eight videos captured by drivers driving through a predefined path wearing
  eye-tracking devices. The dataset includes annotations of billboards, including 154 unique IDs and 155 thousand bounding
  boxes, as well as eye fixation data. We evaluate various object tracking methods in combination with a YOLOv8 detector
  to identify billboard advertisements with the best approach achieving 38.5 HOTA on BillboardLamac. Additionally, we
  train a random forest classifier to classify billboards into three classes based on the length of driver fixations
  achieving 75.8% test accuracy. An analysis of the trained classifier reveals that the duration of billboard visibility,
  its saliency, and size are the most influential features when assessing billboard significance.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat.

tags:
  - Comenius University Bratislava
featured: false

#links:
#  - name: Zenodo
#    url: https://zenodo.org/records/10694437
#url_pdf: 
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - internal-project

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides:
---
