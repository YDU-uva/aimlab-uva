---
title: "Learning to Learn with Variational Information Bottleneck for Domain Generalization"
authors:
- Yingjun Du
- Jun Xu 
- Huan Xiong
- Qiang Qiu 
- Xiantong Zhen 
- Cees G.M. Snoek
- Ling Shao
- 
date: "2020-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ECCV 2020*
publication_short: In *ECCV*

abstract: Domain generalization models learn to generalize to previously unseen domains, but suffer from prediction uncertainty and domain shift. In this paper, we address both problems. We introduce a probabilistic meta-learning model for domain generalization, in which classifier parameters shared across domains are modeled as distributions. This enables better handling of prediction uncertainty on unseen domains. To deal with domain shift, we learn domain-invariant representations by the proposed principle of meta variational information bottleneck, we call MetaVIB. MetaVIB is derived from novel variational bounds of mutual information, by leveraging the meta-learning setting of domain generalization. Through episodic training, MetaVIB learns to gradually narrow domain gaps to establish domain-invariant representations, while simultaneously maximizing prediction accuracy. We conduct experiments on three benchmarks for cross-domain visual recognition. Comprehensive ablation studies validate the benefits of MetaVIB for domain generalization. The comparison results demonstrate our method outperforms previous approaches consistently.

# Summary. An optional shortened abstract.
summary: Meta Learning, Domain Generalization, Variational Inference, Information Bottleneck

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://arxiv.org/abs/2007.07645
url_pdf: https://arxiv.org/pdf/2007.07645.pdf
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
