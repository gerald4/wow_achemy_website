  ---
title: "Global Explanations with Decision Rules: a Co-learning Approach"
authors:
- admin
- Paul Temple
- Benoît Frénay
date: "2021"
#"2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 37th Conference on Uncertainty in Artificial Intelligence*
publication_short: In *UAI*

abstract: Black-box machine learning models can be extremely accurate. Yet, in critical applications such as in healthcare or justice, if models cannot be explained, domain experts will be reluctant to use them.  A common way to explain a black-box model is to approximate it by a simpler model such as a decision tree. In this paper, we propose a co-learning framework to learn decision rules as explanations of black-box models through knowledge distillation and simultaneously constrain the black-box model by these explanations; all of this in a differentiable manner. To do so, we introduce the soft truncated Gaussian mixture analysis (STruGMA), a probabilistic model which encapsulates hyper-rectangle decision rules. With STruGMA, global explanations can be extracted by any rule learner such as decision lists, sets or trees. We provide evidences through experiments that our framework can globally explain differentiable black-box models such as neural networks. In particular, the explanation fidelity is increased, while the accuracy of the models is marginally impacted.

# Summary. An optional shortened abstract.


tags:
- Source Themes
featured: true

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://auai.org/uai2021/pdf/uai2021.231.preliminary.pdf
url_code: 'https://github.com/gerald4/Co-learning_with_STruGMA'
#url_dataset: '#'
url_poster: 'https://github.com/gerald4/Co-learning_with_STruGMA/blob/master/slides_poster/Poster_UAI_Paper_final.pdf'
#url_project: ''  ---
title: "Global Explanations with Decision Rules: a Co-learning Approach"
authors:
- admin
- Paul Temple
- Benoît Frénay
date: "2021"
url_slides: 'https://github.com/gerald4/Co-learning_with_STruGMA/blob/master/slides_poster/Presentation_UAI_final.pdf'
#url_source: '#'
url_video: 'https://underline.io/lecture/28820-231-i-f5-global-explanations-with-decision-rules-a-co-learning-approach'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

<!---
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
!-->
