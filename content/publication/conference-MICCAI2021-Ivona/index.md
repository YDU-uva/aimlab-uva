---
title: "Variational Topic Inference for Chest X-Ray Report Generation"
authors:
- Ivona Najdenkoska
- Xiantong Zhen 
- Marcel Worring
- Ling Shao

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
publication: In *International Conference on Medical Image Computing and Computer Assisted Intervention  2021*
publication_short: In *MICCAI*

abstract: Automating report generation for medical imaging promises to alleviate workload and assist diagnosis in clinical practice. Recent work has shown that deep learning models can successfully caption natural images. However, learning from medical data is challenging due to the diversity and uncertainty inherent in the reports written by diﬀerent radiologists with discrepant expertise and experience. To tackle these challenges, we propose variational topic inference for automatic report generation. Speciﬁcally, we introduce a set of topics as latent variables to guide sentence generation by aligning image and language modalities in a latent space. The topics are inferred in a conditional variational inference framework, with each topic governing the generation of a sentence in the report. Further, we adopt a visual attention module that enables the model to attend to diﬀerent local regions in the image to generate more informative descriptions. We conduct extensive experiments on two benchmarks, namely Indiana U. Chest X-rays and MIMIC-CXR. The results demonstrate that our proposed variational topic inference model can generate reports which are not mere copies of reports used in training, while still achieving comparable performance to state-of-the-art methods in terms of standard language generation criteria.

# Summary. An optional shortened abstract.
summary: We propose  variational topic inference for automatic report generation.
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
