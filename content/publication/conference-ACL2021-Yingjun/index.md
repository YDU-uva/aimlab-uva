---
title: "Meta-Learning with Variational Semantic Memory for Word Sense Disambiguation"
authors:
- Yingjun Du
- Nithin Holla
- Xiantong Zhen
- Cees G.M. Snoek
- Ekaterina Shutova

- 
date: "2021-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Annual Meeting of the Association for Computational Linguistics 2021*
publication_short: In *ACL*

abstract: A critical challenge faced by supervised word sense disambiguation (WSD) is the lack of large annotated datasets with sufﬁcient coverage of words in their diversity of senses. This inspired recent research on few-shot WSD using meta-learning. While such work has successfully applied meta-learning to learn new word senses from very few examples, its performance still lags behind its fully-supervised counterpart. Aiming to further close this gap, we propose a model of semantic memory for WSD in a meta-learning setting. Semantic memory encapsulates prior experiences seen throughout the lifetime of the model, which aids better generalization in limited data settings. Our model is based on hierarchical variational inference and incorporates an adaptive memory update rule via a hypernetwork. We show our model advances the state of the art in few-shot WSD, supports effective learning in extremely data scarce (e.g. one-shot) scenarios and produces meaning prototypes that capture similar senses of distinct words.

# Summary. An optional shortened abstract.
summary: We propose  a model of semantic memory for WSD in a meta-learning setting.
tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://arxiv.org/abs/2106.02960
url_pdf: https://arxiv.org/abs/2106.02960.pdf
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
