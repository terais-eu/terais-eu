---
title: 'Tuning-less Object Naming with a Foundation Model'
authors:
  - Andrej Lúčny
  - Pavel Petrovič
date: '2023-11-02T00:00:00Z'
doi: '10.48550/arXiv.2311.04924'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '3' ]

# Publication name and optional abbreviated publication name.
publication: '2023 World Symposium on Digital Intelligence for Systems and Machines'
publication_short: 'DISA 2023'

abstract: |
  We implement a real-time object naming system that enables learning a set of named entities never seen. Our approach
  employs an existing foundation model that we consider ready to see anything before starting. It turns seen images into
  relatively small feature vectors that we associate with index to a gradually built vocabulary without any training of
  fine-tuning of the model. Our contribution is using the association mechanism known from transformers as attention. It
  has features that support generalization from irrelevant information for distinguishing the entities and potentially
  enable associating with much more than indices to vocabulary. As a result, the system can work in a one-shot manner
  and correctly name objects named in different contents. We also outline implementation details of the system modules
  integrated by a blackboard architecture. Finally, we investigate the system's quality, mainly how many objects it can
  handle in this way. 
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Artificial Intelligence
  - Neural and Evolutionary Computing
  - Comenius University Bratislava
featured: false

links:
  - name: arXiv
    url: https://arxiv.org/abs/2311.04924
# links:
#   - name: arXiv
#     url: https://arxiv.org/abs/2305.08528
#   - name: Other formats
#     url: https://arxiv.org/format/2305.08528
url_pdf: https://arxiv.org/pdf/2311.04924.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
#url_source: '#'
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
