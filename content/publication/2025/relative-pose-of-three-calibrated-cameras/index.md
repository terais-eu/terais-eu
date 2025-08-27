---
title: 'Practical solutions to the relative pose of three calibrated cameras'
authors:
  - Charalambos Tzamos
  - viktor-kocur
  - Yaqing Ding
  - Daniel Barath
  - zuzana-berger-haladova
  - Torsten Sattler
  - Zuzana Kulekova
date: '2025-08-13T00:00:00Z'
doi: '10.1109/CVPR52734.2025.01074'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition'
publication_short: 'CVPR'

abstract: |
  We study the challenging problem of estimating the relative pose of three calibrated cameras from four point correspondences. We propose novel efficient solutions to this problem that are based on the simple idea of using four correspondences to estimate an approximate geometry of the first two views. We model this geometry either as an affine or a fully perspective geometry estimated using one additional approximate correspondence. We generate such an approximate correspondence using a very simple and efficient strategy, where the new point is the mean point of three corresponding input points. The new solvers are efficient and easy to implement, since they are based on existing efficient minimal solvers, i.e., the 4-point affine fundamental matrix, the well-known 5-point relative pose solver, and the P3P solver. Extensive experiments on real data show that the proposed solvers, when properly coupled with local optimization, achieve state-of-the-art results, with the novel solver based on approximate mean-point correspondences being more robust and accurate than the affine-based solver.
  
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
