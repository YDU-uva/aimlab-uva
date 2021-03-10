---
title: "Pixel-level Non-local Image Smoothing with Objective Evaluation"
authors:
- Zhiang Liu
- Yingkun Hou
- Xiantong Zhen
- Jun Xu
- Ling Shao
- MingMing Cheng


date: "2020-03-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Multimedia"
publication_short: "TMM"

abstract: Recently, image smoothing has gained increasing attention due to its prerequisite role in other image processing tasks, e.g., image enhancement and editing. However, the evaluation of image smoothing algorithms is usually performed by subjective observation on images without corresponding ground truths. To promote the development of image smoothing algorithms, in this paper, we construct a novel Nankai Smoothing (NKS) dataset containing 200 images blended by versatile structure images and natural textures. The structure images are inherently smooth and naturally taken as ground truths. On our NKS dataset, we comprehensively evaluate 14 popular image smoothing algorithms. Moreover, we propose a Pixel-level NonLocal Smoothing (PNLS) method to well preserve the structure of the smoothed images, by exploiting the pixel-level non-local self-similarity prior of natural images. Extensive experiments on several benchmark datasets demonstrate that our PNLS outperforms previous algorithms on the image smoothing task. Ablation studies also reveal the work mechanism of our PNLS on image smoothing. To further show its effectiveness, we apply our PNLS on several applications such as semantic region smoothing, detail/edge enhancement, and image abstraction.







# Summary. An optional shortened abstract.
summary: Image smoothing, benchmark dataset, performance evaluation, pixel-level non-local self similarity.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://csjunxu.github.io/paper/PNLS.pdf
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
