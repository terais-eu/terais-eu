---
title: 'Controlling the Output of a Generative Model by Latent Feature Vector Shifting'
authors:
  - Robert Belanec
  - Peter Lacko
  - Kristína Malinovská
date: '2023-09-21T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 'Accepted for DISA 2023'
# publication_short: 'ICANN 2023'

abstract: |
  State-of-the-art generative models (e.g. StyleGAN3 \cite{karras2021alias}) often generate photorealistic images based on vectors sampled from their latent space. However, the ability to control the output is limited. Here we present our novel method for latent vector shifting for controlled output image modification utilizing semantic features of the generated images. In our approach we use a pre-trained model of StyleGAN3 that generates images of realistic human faces in relatively high resolution. We complement the generative model with a convolutional neural network classifier, namely ResNet34, trained to classify the generated images with binary facial features from the CelebA dataset. Our latent feature shifter is a neural network model with a task to shift the latent vectors of a generative model into a specified feature direction. We have trained latent feature shifter for multiple facial features, and outperformed our baseline method in the number of generated images with the desired feature. To train our latent feature shifter neural network, we have designed a dataset of pairs of latent vectors with and without a certain feature. Based on the evaluation, we conclude that our latent feature shifter approach was successful in the controlled generation of the StyleGAN3 generator.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Neural and Evolutionary Computing
  - Artificial Intelligence
  - Image Processing
  - DISA 2023
  - Comenius University Bratislava
featured: false

links:
  - name: DISA 2023
    url: https://www.disa2023.org/
#   - name: Other formats
#     url: https://arxiv.org/format/2305.08528
# url_pdf: https://arxiv.org/pdf/2305.08528
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
