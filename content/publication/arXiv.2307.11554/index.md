---
title: 'CycleIK: Neuro-inspired Inverse Kinematics'
authors:
  - Jan-Gerrit Habekost
  - Erik Strahl
  - Philipp Allgeuer
  - Matthias Kerzel
  - Stefan Wermter
date: '2023-07-21T00:00:00Z'
doi: '10.48550/arXiv.2307.11554'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 'arXiv:2307.11554. Accepted for ICANN 2023'
# publication_short: 'ICANN 2023'

abstract: The paper introduces CycleIK, a neuro-robotic approach that wraps two novel neuro-inspired methods for the inverse kinematics (IK) task, a Generative Adversarial Network (GAN), and a Multi-Layer Perceptron architecture. These methods can be used in a standalone fashion, but we also show how embedding these into a hybrid neuro-genetic IK pipeline allows for further optimization via sequential least-squares programming (SLSQP) or a genetic algorithm (GA). The models are trained and tested on dense datasets that were collected from random robot configurations of the new Neuro-Inspired COLlaborator (NICOL), a semi-humanoid robot with two redundant 8-DoF manipulators. We utilize the weighted multi-objective function from the state-of-the-art BioIK method to support the training process and our hybrid neuro-genetic architecture. We show that the neural models can compete with state-of-the-art IK approaches, which allows for deployment directly to robotic hardware. Additionally, it is shown that the incorporation of the genetic algorithm improves the precision while simultaneously reducing the overall runtime.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Robotics
  - Artificial Intelligence
  - ICANN 2023
  - University of Hamburg
featured: false

links:
  # - name: arXiv
  #   url: https://arxiv.org/abs/2307.11554
  - name: Other formats
    url: https://arxiv.org/format/2307.11554
url_pdf: https://arxiv.org/pdf/2307.11554
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
