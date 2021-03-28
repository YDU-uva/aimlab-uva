---
title: "Variational Prototype Inference for Few-Shot Semantic Segmentation"
authors:
- Haochen Wang
- Yandan Yang
- Xianbin Cao
- Xiantong Zhen
- Cees G.M. Snoek
- Ling Shao

- 
date: "2021-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *WACV 2021*
publication_short: In *WACV*

abstract: In this paper, we propose variational prototype inference to address few-shot semantic segmentation in a probabilistic framework. A probabilistic latent variable model infers the distribution of the prototype that is treated as the latent variable. We formulate the optimization as a variational inference problem, which is established with an amortized inference network based on an auto-encoder architecture. The probabilistic modeling of the prototype enhances its generalization ability to handle the inherent uncertainty caused by limited data and the huge intra-class variations of objects. Moreover, it offers a principled way to incorporate the prototype extracted from support images into the prediction of the segmentation maps for query images. We conduct extensive experimental evaluations on three benchmark datasets. Ablation studies show the effectiveness of variational prototype inference for few-shot semantic segmentation by probabilistic modeling. On all three benchmarks, our proposal achieves high segmentation accuracy and surpasses previous methods by considerable margins.

# Summary. An optional shortened abstract.
summary: This paper propose variational prototype inference to address few-shot semantic segmentation in a probabilistic framework.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://openaccess.thecvf.com/content/WACV2021/papers/Wang_Variational_Prototype_Inference_for_Few-Shot_Semantic_Segmentation_WACV_2021_paper.pdf
url_pdf: https://openaccess.thecvf.com/content/WACV2021/papers/Wang_Variational_Prototype_Inference_for_Few-Shot_Semantic_Segmentation_WACV_2021_paper.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

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
slides:
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
