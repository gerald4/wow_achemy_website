---
title: "Squeeze-SegNet: a new fast deep convolutional neural network for semantic segmentation"
authors:
- admin
- Azeddine Elhassouny
-  Rachid Oulad Haj Thami
date: "2018"
#"2018-07-01T00:00:00Z"


# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 29th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning*
publication_short: In *ICMV*

abstract: The recent researches in Deep Convolutional Neural Network have focused their attention on improving accuracy that provide significant advances. However, if they were limited to classification tasks, nowadays with contributions from Scientific Communities who are embarking in this field, they have become very useful in higher level tasks such as object detection and pixel-wise semantic segmentation. Thus, brilliant ideas in the field of semantic segmentation with deep learning have completed the state of the art of accuracy, however this architectures become very difficult to apply in embedded systems as is the case for autonomous driving. We present a new Deep fully Convolutional Neural Network for pixel-wise semantic segmentation which we call Squeeze-SegNet. The architecture is based on Encoder-Decoder style. We use a SqueezeNet-like encoder and a decoder formed by our proposed squeeze-decoder module and upsample layer using downsample indices like in SegNet and we add a deconvolution layer to provide final multi-channel feature map. On datasets like Camvid or City-states, our net gets SegNet-level accuracy with less than 10 times fewer parameters than SegNet.

tags:
- Source Themes
featured: true

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/1711.05491.pdf
#url_code: 'https://github.com/gerald4/Co-learning_with_STruGMA'
#url_dataset: '#'
#url_poster: 'https://github.com/gerald4/Co-learning_with_STruGMA/blob/master/slides_poster/Poster_UAI_Paper_final.pdf'
#url_project: ''
#url_slides: 'https://github.com/gerald4/Co-learning_with_STruGMA/blob/master/slides_poster/Presentation_UAI_final.pdf'
#url_source: '#'
#url_video: 'https://underline.io/lecture/28820-231-i-f5-global-explanations-with-decision-rules-a-co-learning-approach'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Architecture.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

