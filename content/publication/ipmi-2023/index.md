---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Neural Implicit k-Space for Binning-Free Non-Cartesian Cardiac MR Imaging."
authors: [W. Huang, H. B. Li, J. Pan, G. Cruz, D. Rueckert, K. Hammernik,]
date: 2023-06-08
doi: "https://doi.org/10.1007/978-3-031-34048-2_42"

# Schedule page publish date (NOT publication's date).
publishDate: 2024

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Information Processing in Medical Imaging (IPMI), 548-560, 2023."
publication_short: ""

abstract: "In this work, we propose a novel image reconstruction framework that directly learns a neural implicit representation in k-space for ECG-triggered non-Cartesian Cardiac Magnetic Resonance Imaging (CMR). While existing methods bin acquired data from neighboring time points to reconstruct one phase of the cardiac motion, our framework allows for a continuous, binning-free, and subject-specific k-space representation. We assign a unique coordinate that consists of time, coil index, and frequency domain location to each sampled k-space point. We then learn the subject-specific mapping from these unique coordinates to k-space intensities using a multi-layer perceptron with frequency domain regularization. During inference, we obtain a complete k-space for Cartesian coordinates and an arbitrary temporal resolution. A simple inverse Fourier transform recovers the image, eliminating the need for density compensation and costly non-uniform Fourier transforms for non-Cartesian data. This novel imaging framework was tested on 42 radially sampled datasets from 6 subjects. The proposed method outperforms other techniques qualitatively and quantitatively using data from four and one heartbeat(s) and 30 cardiac phases. Our results for one heartbeat reconstruction of 50 cardiac phases show improved artifact removal and spatio-temporal resolution, leveraging the potential for real-time CMR."

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
