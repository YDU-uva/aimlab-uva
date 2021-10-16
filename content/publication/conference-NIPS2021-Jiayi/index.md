---
title: "Variational Multi-Task Learning with Gumbel-Softmax Priors"
authors:
- Jiayi Shen
- Xiantong Zhen
- Marcel Worring
- Ling Shao
date: "2021-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Pateant
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS 2021*
publication_short: In *NeurIPS*

abstract: Multi-task learning aims to explore task relatedness to improve individual tasks, which is of particular signiﬁcance in the challenging scenario that only limited data is available for each task. To tackle this challenge, we propose variational multi-task learning (VMTL), a general probabilistic inference framework in which we cast multi-task learning as a variational Bayesian inference problem. In this way, task relatedness can be explored in a uniﬁed manner by specifying priors. To leverage the knowledge shared among tasks, we design the prior of a task to be a learnable mixture of the variational posteriors of other tasks, which is learned by the Gumbel-Softmax technique. In contrast to previous methods, our VMTL can exploit task relatedness for both representations and classiﬁers in a single uniﬁed framework by jointly inferring their posteriors. This enables individual tasks to fully leverage inductive biases provided by related tasks, therefore improving the overall performance of all tasks. Experimental results demonstrate that the proposed VMTL is able to effectively tackle a variety of challenging multi-task learning problems with limited training data for both classiﬁcation and regression. Our method consistently surpasses previous methods, including strong Bayesian approaches, and achieves state-of-the-art performance on ﬁve benchmark datasets.

# Summary. An optional shortened abstract.
summary: We propose variational multi-task learning (VMTL), a general probabilistic inference framework in which we cast multi-task learning as a variational Bayesian inference problem.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://arxiv.org/abs/2006.06707
url_pdf: https://arxiv.org/pdf/2006.06707.pdf
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
