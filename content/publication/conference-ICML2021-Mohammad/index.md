---
title: "Kernel Continual Learning"
authors:
- Mohammad Derakhshani
- Xiantong Zhen
- Ling Shao
- Cees G.M. Snoek
date: "2021-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Pateant
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ICML 2021*
publication_short: In *ICML*

abstract: This paper introduces kernel continual learning, a simple but effective variant of continual learning that leverages the non-parametric nature of kernel methods to tackle catastrophic forgetting. We deploy an episodic memory unit that stores a subset of samples for each task to learn task-speciﬁc classiﬁers based on kernel ridge regression. This does not require memory replay and systematically avoids task interference in the classiﬁers. We further introduce variational random features to learn a data-driven kernel for each task. To do so, we formulate kernel continual learning as a variational inference problem, where a random Fourier basis is incorporated as the latent variable. The variational posterior distribution over the random Fourier basis is inferred from the coreset of each task. In this way, we are able to generate more informative kernels speciﬁc to each task, and, more importantly, the coreset size can be reduced to achieve more compact memory, resulting in more efﬁcient continual learning based on episodic memory. Extensive evaluation on four benchmarks demonstrates the effectiveness and promise of kernels for continual learning.

# Summary. An optional shortened abstract.
summary: We deploy an episodic memory unit that stores a subset of samples for each task to learn task-speciﬁc classiﬁers based on kernel ridge regression. 

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://isis-data.science.uva.nl/cgmsnoek/pub/derakhshani-kernel-continual-icml2021.pdf
url_pdf: https://isis-data.science.uva.nl/cgmsnoek/pub/derakhshani-kernel-continual-icml2021.pdf
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
