---
title: "Few-Shot Semantic Segmentation with Democratic Attention Networks"
authors:
- Haochen Wang
- Xudong Zhang
- Yutao Hu
- Yandan Yang
- Xianbin Cao
- Xiantong Zhen
- 
date: "2020-09-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ECCV 2020*
publication_short: In *ECCV*

abstract: Few-shot segmentation has recently generated great popularity, addressing the challenging yet important problem of segmenting objects from unseen categories with scarce annotated support images. The crux of few-shot segmentation is to extract object information from the support image and then propagate it to guide the segmentation of query images. In this paper, we propose the Democratic Attention Network (DAN) for few-shot semantic segmentation. We introduce the democratized graph attention mechanism, which can activate more pixels on the object to establish a robust correspondence between support and query images. Thus, the network is able to propagate more guiding information of foreground objects from support to query images, enhancing its robustness and generalizability to new objects. Furthermore, we propose multi-scale guidance by designing a refinement fusion unit to fuse features from intermediate layers for the segmentation of the query image. This offers an efficient way of leveraging multi-level semantic information to achieve more accurate segmentation. Extensive experiments on three benchmarks demonstrate that the proposed DAN achieves the new state-of-the-art performance, surpassing the previous methods by large margins. The thorough ablation studies further reveal its great effectiveness for few-shot semantic segmentation



# Summary. An optional shortened abstract.
summary: Few-Shot Segmentation, Graph Attention, Democratic Attention Network, Multi-Scale Guidance

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580715.pdf
url_pdf: http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123580715.pdf
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
