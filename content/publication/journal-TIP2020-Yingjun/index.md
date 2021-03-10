---
title: "Conditional Variational Image Deraining"
authors:
- Yingjun Du 
- Jun Xu 
- Xiantong Zhen
- MingMing Cheng
-  Ling Shao
date: "2020-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing"
publication_short: ""

abstract: Image deraining is an important yet challenging image processing task. Though deterministic image deraining methods are developed with encouraging performance, they are infeasible to learn flexible representations for probabilistic inference and diverse predictions. Besides, rain intensity varies both in spatial locations and across color channels, making this task more difficult. In this paper, we propose a Conditional Variational Image Deraining (CVID) network for better deraining performance, leveraging the exclusive generative ability of Conditional Variational Auto-Encoder (CVAE) on providing diverse predictions for the rainy image. To perform spatially adaptive deraining, we propose a spatial density estimation (SDE) module to estimate a rain density map for each image. Since rain density varies across different color channels, we also propose a channel-wise (CW) deraining scheme. Experiments on synthesized and real-world datasets show that the proposed CVID network achieves much better performance than previous deterministic methods on image deraining. Extensive ablation studies validate the effectiveness of the proposed SDE module and CW scheme in our CVID network.

# Summary. An optional shortened abstract.
summary: In this paper, we propose a Conditional Variational Image Deraining (CVID) network for better deraining performance, leveraging the exclusive generative ability of Conditional Variational Auto-Encoder (CVAE) on providing diverse predictions for the rainy image.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2004.11373.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
