---
title: 'Detection of Vascular Leukoencephalopathy in CT Images'
authors:
  - Zuzana Černeková
  - Viktor Sisik
  - Fatana Jafari
date: '2024-11-29T00:00:00Z'
doi: '10.1007/978-3-031-77915-2_12'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '44th International Conference on Artificial Intelligence'
publication_short: 'SGAI'

abstract: |
  Artificial intelligence (AI) has seen a significant surge in popularity, particularly in its application to medicine. This study explores AI’s role in diagnosing leukoencephalopathy, a small vessel disease of the brain, and a leading cause of vascular dementia and hemorrhagic strokes. We utilized a dataset of approximately 1200 patients with axial brain CT scans to train convolutional neural networks (CNNs) for binary disease classification. Addressing the challenge of varying scan dimensions due to different patient physiologies, we processed the data to a uniform size and applied three preprocessing methods to improve model accuracy. We compared four neural network architectures: ResNet50, ResNet50 3D, ConvNext, and Densenet. The ConvNext model achieved the highest accuracy of 98.5% without any preprocessing, outperforming models with 3D convolutions. To gain insights into model decision-making, we implemented Grad-CAM heatmaps, which highlighted the focus areas of the models on the scans. Our results demonstrate that AI, particularly the ConvNext architecture, can significantly enhance diagnostic accuracy for leukoencephalopathy. This study underscores AI’s potential in advancing diagnostic methodologies for brain diseases and highlights the effectiveness of CNNs in medical imaging applications.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat.

tags:
  - Comenius University Bratislava
featured: false

#links:
#  - name: Zenodo
#    url: https://zenodo.org/records/10694437
#url_pdf: 
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
