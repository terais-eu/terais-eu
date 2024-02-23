---
title: 'Enhancement of 3D Camera Synthetic Training Data with Noise Models'
authors:
  - Katarína Osvaldová
  - Lukáš Gajdošech
  - Viktor Kocur
  - Martin Madaras
date: '2024-02-14T00:00:00Z'
doi: '10.5281/zenodo.10694437'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '27th Computer Vision Winter Workshop'
publication_short: 'CVWW'

abstract: |
  The goal of this paper is to assess the impact of noise in 3D camera-captured data by modeling the noise of the
  imaging process and applying it on synthetic training data. We compiled a dataset of specifically constructed scenes
  to obtain a noise model. We specifically model lateral noise, affecting the position of captured points in the image
  plane, and axial noise, affecting the position along the axis perpendicular to the image plane. The estimated models
  can be used to emulate noise in synthetic training data. The added benefit of adding artificial noise is evaluated in
  an experiment with rendered data for object segmentation. We train a series of neural networks with varying levels of
  noise in the data and measure their ability to generalize on real data. The results show that using too little or too
  much noise can hurt the networks' performance indicating that obtaining a model of noise from real scanners is
  beneficial for synthetic data generation.

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
