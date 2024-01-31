---
title: 'Safe Reinforcement Learning in a Simulated Robotic Arm'
authors:
  - Luka Kovač
  - Igor Fargaš
date: '2023-09-22T00:00:00Z'
doi: '10.1007/978-3-031-44207-0_53'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: 'Accepted for ICANN 2023'
publication_short: 'ICANN 2023'

abstract: |
  Reinforcement learning (RL) agents need to explore their environments in order to learn optimal policies. In many
  environments and tasks, safety is of critical importance. The widespread use of simulators offers a number of
  advantages, including safe exploration which will be inevitable in cases when RL systems need to be trained directly
  in the physical environment (e.g. in human-robot interaction). The popular Safety Gym library offers three mobile
  agent types that can learn goal-directed tasks while considering various safety constraints. In this paper, we extend
  the applicability of safe RL algorithms by creating a customized environment with Panda robotic arm where Safety Gym
  algorithms can be tested. We performed pilot experiments with the popular PPO algorithm comparing the baseline with
  the constrained version and show that the constrained version is able to learn the equally good policy while better
  complying with safety constraints and taking longer training time as expected.

tags:
  - Artificial Intelligence
  - Neural and Evolutionary Computing
  - ICANN 2023
  - Comenius University Bratislava
featured: false
#
links:
  - name: ICANN 2023
    url: https://e-nns.org/icann2023/
#   - name: Other formats
#     url: https://arxiv.org/format/2305.08528
# url_pdf: https://arxiv.org/pdf/2305.08528
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
#url_source: 'https://www.sciencedirect.com/science/article/pii/S0950584923002240'
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
