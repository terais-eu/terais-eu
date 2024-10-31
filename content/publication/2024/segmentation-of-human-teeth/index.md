---
title: "Processing and Segmentation of Human Teeth from 2D Images using Weakly Supervised Learning"
authors:
  - Tomáš Kunzo
  - Viktor Kocur
  - Lukáš Gajdošech
  - Martin Madaras

date: '2023-11-10T00:00:00Z'
doi: '10.1109/DISA59116.2023.10308924'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '2023 World Symposium on Digital Intelligence for Systems and Machines'
publication_short: 'DISA'

abstract: |
  Teeth segmentation is an essential task in dental image analysis for accurate diagnosis and treatment planning. While
  supervised deep learning methods can be utilized for teeth segmentation, they often require extensive manual annotation
  of segmentation masks, which is time-consuming and costly. In this research, we propose a weakly supervised approach for
  teeth segmentation that reduces the need for manual annotation. Our method utilizes the output heatmaps and intermediate
  feature maps from a keypoint detection network to guide the segmentation process. We introduce the TriDental dataset,
  consisting of 3000 oral cavity images annotated with teeth keypoints, to train a teeth keypoint detection network. We
  combine feature maps from different layers of the keypoint detection network, enabling accurate teeth segmentation
  without explicit segmentation annotations. The detected keypoints are also used for further refinement of the
  segmentation masks. Experimental results on the TriDental dataset demonstrate the superiority of our approach in terms
  of accuracy and robustness compared to state-of-the-art segmentation methods. Our method offers a cost-effective and
  efficient solution for teeth segmentation in real-world dental applications, eliminating the need for extensive manual
  annotation efforts.

# Summary. An optional shortened abstract.
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

