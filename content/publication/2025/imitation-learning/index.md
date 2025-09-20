---
title: 'LLM-based Interactive Imitation Learning for Robotic Manipulation'
authors:
  - Jonas Werner
  - Kun Chu
  - Cornelius Weber
  - Stefan Wermter
date: '2025-04-30T00:00:00Z'
doi: '10.48550/arXiv.2504.21769'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '2025 International Joint Conference on Neural Networks'
publication_short: 'IJCNN'

abstract: |
    Recent advancements in machine learning provide methods to train autonomous agents capable of handling the increasing complexity of sequential decision-making in robotics. Imitation Learning (IL) is a prominent approach, where agents learn to control robots based on human demonstrations. However, IL commonly suffers from violating the independent and identically distributed (i.i.d) assumption in robotic tasks. Interactive Imitation Learning (IIL) achieves improved performance by allowing agents to learn from interactive feedback from human teachers. Despite these improvements, both approaches come with significant costs due to the necessity of human involvement. Leveraging the emergent capabilities of Large Language Models (LLMs) in reasoning and generating human-like responses, we introduce LLM-iTeach -- a novel IIL framework that utilizes an LLM as an interactive teacher to enhance agent performance while alleviating the dependence on human resources. Firstly, LLM-iTeach uses a hierarchical prompting strategy that guides the LLM in generating a policy in Python code. Then, with a designed similarity-based feedback mechanism, LLM-iTeach provides corrective and evaluative feedback interactively during the agent's training. We evaluate LLM-iTeach against baseline methods such as Behavior Cloning (BC), an IL method, and CEILing, a state-of-the-art IIL method using a human teacher, on various robotic manipulation tasks. Our results demonstrate that LLM-iTeach surpasses BC in the success rate and achieves or even outscores that of CEILing, highlighting the potential of LLMs as cost-effective, human-like teachers in interactive learning environments. We further demonstrate the method's potential for generalization by evaluating it on additional tasks.

tags:
  - University of Hamburg
featured: false

links:
  - name: code
    url: https://github.com/Tubicor/LLM-iTeach
# url_pdf: '#'
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
