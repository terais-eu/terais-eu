---
title: "Supersampling of Data from Structured-light Scanner with Deep Learning"
authors:
  - Marek Melicherčík
  - Lukáš Gajdošech
  - Viktor Kocur
  - Martin Madaras

date: '2023-11-10T00:00:00Z'
doi: '10.1109/DISA59116.2023.10308923'

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
  This paper focuses on increasing the resolution of depth maps obtained from 3D cameras using structured light
  technology. Two deep learning models FDSR and DKN are modified to work with high-resolution data, and data
  pre-processing techniques are implemented for stable training. The models are trained on our custom dataset of 1200 3D
  scans. The resulting high-resolution depth maps are evaluated using qualitative and quantitative metrics. The approach
  for depth map upsampling offers benefits such as reducing the processing time of a pipeline by first downsampling a
  high-resolution depth map, performing various processing steps at the lower resolution and upsampling the resulting
  depth map or increasing the resolution of a point cloud captured in lower resolution by a cheaper device. The
  experiments demonstrate that the FDSR model excels in terms of faster processing time, making it a suitable choice for
  applications where speed is crucial. On the other hand, the DKN model provides results with higher precision, making it
  more suitable for applications that prioritize accuracy.

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
