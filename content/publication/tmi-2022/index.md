---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Self-supervised Learning for Few-shot Medical Image Segmentation."
authors: [C. Ouyang, C. Biffi, C. Chen, T. Kart, H. Qiu, D. Rueckert,]
date: 2022-07-11
doi: "https://doi.org/10.1109/TMI.2022.3150682"

# Schedule page publish date (NOT publication's date).
publishDate: 2022

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Medical Imaging, 41(7):1837-1848, 2022."
publication_short: ""

abstract: "Fully-supervised deep learning segmentation models are inflexible when encountering new unseen semantic classes and their fine-tuning often requires significant amounts of annotated data. Few-shot semantic segmentation (FSS) aims to solve this inflexibility by learning to segment an arbitrary unseen semantically meaningful class by referring to only a few labeled examples, without involving fine-tuning. State-of-the-art FSS methods are typically designed for segmenting natural images and rely on abundant annotated data of training classes to learn image representations that generalize well to unseen testing classes. However, such a training mechanism is impractical in annotation-scarce medical imaging scenarios. To address this challenge, in this work, we propose a novel self-supervised FSS framework for medical images, named SSL-ALPNet, in order to bypass the requirement for annotations during training. The proposed method exploits superpixel-based pseudo-labels to provide supervision signals. In addition, we propose a simple yet effective adaptive local prototype pooling module which is plugged into the prototype networks to further boost segmentation accuracy. We demonstrate the general applicability of the proposed approach using three different tasks: organ segmentation of abdominal CT and MRI images respectively, and cardiac segmentation of MRI images. The proposed method yields higher Dice scores than conventional FSS methods which require manual annotations for training in our experiments."

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
