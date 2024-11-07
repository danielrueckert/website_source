---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Generative myocardial motion tracking via latent space exploration with biomechanics-informed prior."
authors: [C. Qin, S. Wang, C. Chen, W. Bai, D. Rueckert,]
date: 2022-07-15
doi: "https://doi.org/10.1016/j.media.2022.102682"

# Schedule page publish date (NOT publication's date).
publishDate: 2024

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Medical Image Analysis, 83, 2023."
publication_short: ""

abstract: "Myocardial motion and deformation are rich descriptors that characterize cardiac function. Image registration, as the most commonly used technique for myocardial motion tracking, is an ill-posed inverse problem which often requires prior assumptions on the solution space. In contrast to most existing approaches which impose explicit generic regularization such as smoothness, in this work we propose a novel method that can implicitly learn an application-specific biomechanics-informed prior and embed it into a neural network-parameterized transformation model. Particularly, the proposed method leverages a variational autoencoder-based generative model to learn a manifold for biomechanically plausible deformations. The motion tracking then can be performed via traversing the learnt manifold to search for the optimal transformations while considering the sequence information. The proposed method is validated on three public cardiac cine MRI datasets with comprehensive evaluations. The results demonstrate that the proposed method can outperform other approaches, yielding higher motion tracking accuracy with reasonable volume preservation and better generalizability to varying data distributions. It also enables better estimates of myocardial strains, which indicates the potential of the method in characterizing spatiotemporal signatures for understanding cardiovascular diseases."

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
