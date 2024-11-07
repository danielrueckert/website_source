---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Concurrent ischemic lesion age estimation and segmentation of CT brain using a Transformer-based network."
authors: [A. Marcus, P. Bentley, D. Rueckert,]
date: 2023-06-19
doi: "https://doi.org/10.1109/TMI.2023.3287361"

# Schedule page publish date (NOT publication's date).
publishDate: 2022

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Medical Imaging, 42(12):3464-3473, 2023"
publication_short: ""

abstract: "The cornerstone of stroke care is expedient management that varies depending on the time since stroke onset. Consequently, clinical decision making is centered on accurate knowledge of timing and often requires a radiologist to interpret Computed Tomography (CT) of the brain to confirm the occurrence and age of an event. These tasks are particularly challenging due to the subtle expression of acute ischemic lesions and the dynamic nature of their appearance. Automation efforts have not yet applied deep learning to estimate lesion age and treated these two tasks independently, so, have overlooked their inherent complementary relationship. To leverage this, we propose a novel end-to-end multi-task transformer-based network optimized for concurrent segmentation and age estimation of cerebral ischemic lesions. By utilizing gated positional self-attention and CT-specific data augmentation, the proposed method can capture long-range spatial dependencies while maintaining its ability to be trained from scratch under low-data regimes commonly found in medical imaging. Furthermore, to better combine multiple predictions, we incorporate uncertainty by utilizing quantile loss to facilitate estimating a probability density function of lesion age. The effectiveness of our model is then extensively evaluated on a clinical dataset consisting of 776 CT images from two medical centers. Experimental results demonstrate that our method obtains promising performance, with an area under the curve (AUC) of 0.933 for classifying lesion ages less than 4.5 hours compared to 0.858 using a conventional approach, and outperforms task-specific state-of-the-art algorithms.
"

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
