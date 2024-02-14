---
title: 'Robot at the Mirror: Learning to Imitate via Associating Self-Supervised Models'
authors:
  - Andrej Lúčny
  - Kristína Malinovská
  - Igor Farkaš
date: '2023-09-22T00:00:00Z'
doi: '10.1007/978-3-031-44207-0_39'

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
  We introduce an approach to building a custom model from ready-made self-supervised models via their associating
  instead of training and fine-tuning. We demonstrate it with an example of a humanoid robot looking at the mirror and
  learning to detect the 3D pose of its own body from the image it perceives.
  To build our model, we first obtain features from the visual input and the postures of the robot's body via models
  prepared before the robot's operation. Then we map their corresponding latent spaces by a sample-efficient robot's
  self-exploration at the mirror. In this way, the robot builds the solicited 3D pose detector, which quality is
  immediately perfect on the acquired samples instead of obtaining the quality gradually. The mapping, which employs
  associating the pairs of feature vectors, is then implemented in the same way as the key--value mechanism of the
  famous transformer models. Finally, deploying our model for imitation to a simulated robot allows us to study, tune up
  and systematically evaluate its hyperparameters without the involvement of the human counterpart, advancing our
  previous research.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Robotics
  - Neural and Evolutionary Computing
  - Artificial Intelligence
  - ICANN 2023
  - Comenius University Bratislava
featured: false

links:
  - name: ICANN 2023
    url: https://e-nns.org/icann2023/
# links:
#   - name: arXiv
#     url: https://arxiv.org/abs/2305.08528
#   - name: Other formats
#     url: https://arxiv.org/format/2305.08528
#url_pdf: https://link.springer.com/content/pdf/10.1007/978-3-031-44207-0_39
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
