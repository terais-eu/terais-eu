---
title: 'Robotic Calibration Based on Haptic Feedback Improves Sim-to-Real Transfer'
authors:
  - Juraj Gavura
  - Michal Vavrečka
  - Igor Farkaš
  - Connor Gäde
date: '2025-09-23T00:00:00Z'
doi: '10.1007/978-3-032-04552-2_14'

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
  When inverse kinematics (IK) is adopted to control robotic arms in manipulation tasks, there is often a discrepancy between the end effector (EE) position of the robot model in the simulator and the physical EE in reality. In most robotic scenarios with sim-to-real transfer, we have information about joint positions in both simulation and reality, but the EE position is only available in simulation. We developed a novel method to overcome this difficulty based on haptic feedback calibration, using a touchscreen in front of the robot that provides information on the EE position in the real environment. During the calibration procedure, the robot touches specific points on the screen, and the information is stored. In the next stage, we build a transformation function from the data based on linear transformation and neural networks that is capable of outputting all missing variables from any partial input (simulated/real joint/EE position). Our results demonstrate that a fully nonlinear neural network model performs best, significantly reducing positioning errors.
  
tags:
  - Comenius University Bratislava
  
featured: false

links:
  - name: arXiv
    url: https://arxiv.org/abs/2507.08572
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
