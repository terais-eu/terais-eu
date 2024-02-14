---
title: 'Neural Field Conditioning Strategies for 2D Semantic Segmentation'
authors:
  - Martin Gromniak
  - Sven Magg
  - Stefan Wermter
date: '2023-09-22T00:00:00Z'
doi: '10.1007/978-3-031-44210-0_42'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: 'International Conference on Artificial Neural Networks 2023'
publication_short: 'ICANN 2023'

abstract: |
  Neural fields are neural networks which map coordinates to a desired signal. When a neural field should jointly model
  multiple signals, and not memorize only one, it needs to be conditioned on a latent code which describes the signal at
  hand. Despite being an important aspect, there has been little research on conditioning strategies for neural fields.
  In this work, we explore the use of neural fields as decoders for 2D semantic segmentation. For this task, we compare
  three conditioning methods, simple concatenation of the latent code, Feature Wise Linear Modulation (FiLM), and
  Cross-Attention, in conjunction with latent codes which either describe the full image or only a local region of the
  image. Our results show a considerable difference in performance between the examined conditioning strategies.
  Furthermore, we show that conditioning via Cross-Attention achieves the best results and is competitive with a
  CNN-based decoder for semantic segmentation.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Computer Vision and Pattern Recognition
  - Machine Learning
  - Image and Video Processing
  - ICANN 2023
  - University of Hamburg
featured: false

links:
  - name: ICANN 2023
    url: https://e-nns.org/icann2023/
url_pdf: https://link.springer.com/content/pdf/10.1007/978-3-031-44210-0_42
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
