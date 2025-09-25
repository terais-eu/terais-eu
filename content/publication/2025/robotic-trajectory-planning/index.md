---
title: 'Towards Bio-inspired Robotic Trajectory Planning via Self-supervised RNN'
authors:
  - Miroslav Cibula
  - Kristína Malinovská
  - Matthias Kerzel
date: '2025-09-23T00:00:00Z'
doi: '10.1007/978-3-032-04552-2_15'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '2025 Artificial Neural Networks and Machine Learning'
publication_short: 'ICANN'

abstract: |
  Trajectory planning in robotics is understood as generating a sequence of joint configurations that will lead a robotic agent, or its manipulator, from an initial state to the desired final state, thus completing a manipulation task while considering constraints like robot kinematics and the environment. Typically, this is achieved via sampling-based planners, which are computationally intensive. Recent advances demonstrate that trajectory planning can also be performed by supervised sequence learning of trajectories, often requiring only a single or fixed number of passes through a neural architecture, thus ensuring a bounded computation time. Such fully supervised approaches, however, perform imitation learning; they do not learn based on whether the trajectories can successfully reach a goal, but try to reproduce observed trajectories. In our work, we build on this approach and propose a cognitively inspired self-supervised learning scheme based on a recurrent architecture for building a trajectory model. We evaluate the feasibility of the proposed method on a task of kinematic planning for a robotic arm. The results suggest that the model is able to learn to generate trajectories only using given paired forward and inverse kinematics models, and indicate that this novel method could facilitate planning for more complex manipulation tasks requiring adaptive solutions.
tags:
  - Comenius University Bratislava
featured: false

links:
  - name: arXiv
    url: https://arxiv.org/abs/2507.02171
#url_pdf: '#'
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
