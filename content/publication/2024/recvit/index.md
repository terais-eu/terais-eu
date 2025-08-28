---
title: 'RecViT: Enhancing Vision Transformer with Top-Down Information Flow '
authors:
  - stefan-pocos
  - iveta-beckova
  - igor-farkas
date: '2024-03-31T00:00:00Z'
doi: '10.5220/0012464700003660'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ '1' ]

# Publication name and optional abbreviated publication name.
publication: '19th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications'
publication_short: 'VISAPP'

abstract: |
  We propose and analyse a novel neural network architecture — recurrent vision transformer (RecViT). Building upon the popular vision transformer (ViT), we add a biologically inspired top-down connection, letting the network ‘reconsider’ its initial prediction. Moreover, using a recurrent connection creates space for feeding multiple similar, yet slightly modified or augmented inputs into the network, in a single forward pass. As it has been shown that a top-down connection can increase accuracy in case of convolutional networks, we analyse our architecture, combined with multiple training strategies, in the adversarial examples (AEs) scenario. Our results show that some versions of RecViT indeed exhibit more robust behaviour than the baseline ViT, on the tested datasets yielding ≈18 % and ≈22 % absolute improvement in robustness while the accuracy drop was only ≈1%. We also leverage the fact that transformer networks have certain level of inherent explainability. By visualising atte ntion maps of various input images, we gain some insight into the inner workings of our network. Finally, using annotated segmentation masks, we numerically compare the quality of attention maps on original and adversarial images.

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
