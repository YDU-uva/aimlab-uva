---
title: "Few-Shot Ensemble Learning for Video Classification with SlowFast Memory Networks"
authors:
- Mengshi Qi
- Jie Qin
- Xiantong Zhen
- Di Huang
- Yi Yang
- Jiebo Luo

- 
date: "2020-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ECCV 2020*
publication_short: In *ECCV*

abstract: In the era of big data, few-shot learning has recently received much attention in multimedia analysis and computer vision due to its appealing ability of learning from scarce labeled data. However, it has been largely underdeveloped in the video domain, which is even more challenging due to the huge spatial-temporal variability of video data. In this paper, we address few-shot video classification by learning an ensemble of SlowFast networks augmented with memory units. Specifically, we introduce a family of few-shot learners based on SlowFast networks which are used to extract informative features at multiple rates, and we incorporate a memory unit into each network to enable encoding and retrieving crucial information instantly. Furthermore, we propose a choice controller network to leverage the diversity of few-shot learners by learning to adaptively assign a confidence score to each SlowFast memory network, leading to a strong classifier for enhanced prediction. Experimental results on two widely-adopted video datasets demonstrate the effectiveness of the proposed method, as well as its superior performance over the state-of-the-art approaches.



# Summary. An optional shortened abstract.
summary: In this paper, we address few-shot video classification by learning an ensemble of SlowFast networks augmented with memory units.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://dl.acm.org/doi/abs/10.1145/3394171.3416269
url_pdf: https://dl.acm.org/doi/abs/10.1145/3394171.3416269
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
