---
title: 'Replay to Remember: Continual Layer-Specific Fine-tuning for German Speech Recognition'
authors:
  - Theresa Pekarek Rosin
  - Stefan Wermter
date: '2023-09-22T00:00:00Z'
doi: '10.1007/978-3-031-44195-0_40'

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
  While Automatic Speech Recognition (ASR) models have shown significant advances with the introduction of
  unsupervised or self-supervised training techniques, these improvements are still only limited to a subsection of
  languages and speakers. Transfer learning enables the adaptation of large-scale multilingual models to not only
  low-resource languages but also to more specific speaker groups. However, fine-tuning on data from new domains is
  usually accompanied by a decrease in performance on the original domain. Therefore, in our experiments, we examine how
  well the performance of large-scale ASR models can be approximated for smaller domains, with our own dataset of German
  Senior Voice Commands (SVC-de), and how much of the general speech recognition performance can be preserved by
  selectively freezing parts of the model during training. To further increase the robustness of the ASR model to
  vocabulary and speakers outside of the fine-tuned domain, we apply Experience Replay for continual learning. By adding
  only a fraction of data from the original domain, we are able to reach Word-Error-Rates (WERs) below 5% on the new
  domain, while stabilizing performance for general speech recognition at acceptable WERs.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Computation and Language
  - Sound
  - Audio and Speech Processing
  - ICANN 2023
  - University of Hamburg
featured: false

links:
  - name: arXiv
    url: https://arxiv.org/abs/2307.07280
  - name: ICANN 2023
    url: https://e-nns.org/icann2023/
#url_pdf: https://arxiv.org/pdf/2307.07280
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
