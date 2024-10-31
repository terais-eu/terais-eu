---
title: "Robust Self-Calibration of Focal Lengths from the Fundamental Matrix"
authors:
  - Viktor Kocur
  - Daniel Kyselica
  - Zuzana Kukelova

date: '2024-09-16T00:00:00Z'
doi: '10.1109/CVPR52733.2024.00499'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition'
publication_short: 'CVPR'

abstract: |
  The problem of self-calibration of two cameras from a given fundamental matrix is one of the basic problems in geometric
  computer vision. Under the assumption of known principal points and square pixels, the Bougnoux formula offers a means
  to compute the two unknown focal lengths. However, in many practical situations, the formula yields inaccurate results
  due to commonly occurring singularities. Moreover, the estimates are sensitive to noise in the com-puted fundamental
  matrix and to the assumed positions of the principal points. In this paper, we therefore propose an efficient and robust
  iterative method to estimate the focal lengths along with the principal points of the cameras given a fundamental matrix
  and priors for the estimated camera intrinsics. In addition, we study a computationally efficient check of models
  generated within RANSAC that improves the accuracy of the estimated models while reducing the to-tal computational time.
  Extensive experiments on real and synthetic data show that our iterative method brings signifi-cant improvements in
  terms of the accuracy of the estimated focal lengths over the Bougnoux formula and other state-of-the-art methods, even
  when relying on inaccurate priors.

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
