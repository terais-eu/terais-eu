---
title: "Appearance-Based Gaze Estimation Enhanced with Synthetic Images Using Deep Neural Networks"
authors:
  - Dmytro Herashchenko
  - Igor Farkaš
date: '2024-01-01T00:00:00Z'
doi: '10.1109/SSCI52147.2023.10371987'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '2023 IEEE Symposium Series on Computational Intelligence'
publication_short: 'SSCI'

abstract: |
  Human eye gaze estimation is an important cognitive ingredient for successful human-robot interaction, enabling the
  robot to read and predict human behavior. We approach this problem using artificial neural networks and build a modular
  system estimating gaze from separately cropped eyes, taking advantage of existing well-functioning components for face
  detection (RetinaFace) and head pose estimation (6DRepNet). Our proposed method does not require any special hardware or
  infrared filters but uses a standard notebook-builtin RGB camera, as often approached with appearance-based methods.
  Using the MetaHuman tool, we also generated a large synthetic dataset of more than 57,000 human faces and made it
  publicly available. The inclusion of this dataset (with eye gaze and head pose information) on top of the standard
  Columbia Gaze dataset into training the model led to better accuracy with a mean average error below two degrees in eye
  pitch and yaw directions, which compares favourably to related methods. We also verified the feasibility of our model by
  its preliminary testing in real-world setting using the builtin 4K camera in NICO semi-humanoid robot's eye.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat.

tags:
  - Comenius University Bratislava
featured: false

#links:
#  - name: Zenodo
#    url: https://zenodo.org/records/10694437
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10371987
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
