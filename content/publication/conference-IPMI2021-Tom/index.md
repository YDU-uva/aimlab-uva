---
title: "Variational Knowledge Distillation for Disease Classification in Chest X-Rays"
authors:
- Tom van Sonsbeek
- Xiantong Zhen 
- Marcel Worring
- Ling Shao

- 
date: "2021-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Information Processing in Medical Imaging (IPMI) 2021*
publication_short: In *IPMI*

abstract: Disease classification relying solely on imaging data attracts great interest in medical image analysis. Current models could be further improved, however, by also employing Electronic Health Records (EHRs), which contain rich information on patients and findings from clinicians. It is challenging to incorporate this information into disease classification due to the high reliance on clinician input in EHRs, limiting the possibility for automated diagnosis. In this paper, we propose variational knowledge distillation (VKD), which is a new probabilistic inference framework for disease classification based on X-rays that leverages knowledge from EHRs. Specifically, we introduce a conditional latent variable model, where we infer the latent representation of the X-ray image with the variational posterior conditioning on the associated EHR text. By doing so, the model acquires the ability to extract the visual features relevant to the disease during learning and can therefore perform more accurate classification for unseen patients at inference based solely on their X-ray scans. We demonstrate the effectiveness of our method on three public benchmark datasets with paired X-ray images and EHRs. The results show that the proposed variational knowledge distillation can consistently improve the performance of medical image classification and significantly surpasses current methods.

# Summary. An optional shortened abstract.
summary: We propose variational knowledge distillation (VKD), which is a new probabilistic inference framework for disease classification based on X-rays that lever- ages knowledge from EHRs. 
tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://arxiv.org/abs/2103.10825
url_pdf: https://arxiv.org/abs/2103.10825.pdf
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
