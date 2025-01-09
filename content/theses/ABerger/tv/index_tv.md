---
title: "IDP/Guided Research/Thesis: Improving topological correctness with total variation"
date: 2025-01-08
authors: ["AlexBerger", "LaurinLux", "JohannesPaetzold"]
---

Topological correctness, i.e., the preservation of structural integrity and specific characteristics of shape, is a fundamental requirement for medical imaging tasks, such as neuron or vessel segmentation. However, most networks are trained using pixel-wise loss functions such as Dice, neglecting topological accuracy. Recently, significant methodological advancements have applied well-founded concepts from algebraic topology to topologically accurate binary segmentation [1,2,3,4]. However, these solutions are often computational expensive and do not match the runtime speed of pixel-wise loss functions, such as Dice. Total variation is a promising method to efficiently improve topological accuracy with interesting theoretical ties to persistent homology [5]. 


This project focuses on applying total variation as a novel method for efficient topology aware image segmentation. Note that we also offer other projects in the field of topology-preserving image segmentation. For more information, see our profiles.


<br/>

## Methodology

1. Review the current state-of-the-art techniques for topologically accurate image segmentation and total variation in image segmentation.
2. Formulation of a total variation loss for image segmentation.
3. Comparison to existing baseline methods in terms of pixel-wise, overlap-based, and topological accuracy with a focus on computational efficiency. 
4. Preparation and submission of a peer-reviewed publication.

## Your qualifications:


We are looking for a highly motivated student in Computer Science, Mathematics, Physics or Engineering. Your goal is to explore the potential of total variation as an efficient method for topology-aware image segmentation. You will be working with Alex and Laurin, two PhD candidates at TU Munich, and Johannes, an appointed assistant professor at Cornell University. Prof. Daniel Rueckert will be the project supervisor. Importantly, we aim to publish the results of this work with you in a follow-up study at a high-impact machine learning conference or in an academic journal. 

**Requirements:**

1. Strong motivation and interest in machine learning.
2. Strong academic record (e.g. high GPA in current and previous studies).
3. Advanced programming skills in C++, Python or C.
4. Enthusiasm for teamwork and interdisciplinary research.

<br/>

## What we offer:

- An exciting research project with many possibilities for bringing your own ideas into the field.
- Close supervision and access to state-of-the-art computer hardware.
- Hands-on experience with state-of-the-art machine learning architectures.
- The chance to work in a collaborative (TUM and Cornell) team of highly qualified experts in machine learning, computer vision, and deep learning.

<br/>

## How to apply:

Just send an email to a.berger@tum.de, laurin.lux@tum.de, and jpaetzold@med.cornell.edu, with a short CV and your grade report. We promise to get back to you within days.

<br/>

## References:

[1] Lux, L., Berger, A. H., Weers, A., Stucki, N., Rueckert, D., Bauer, U., & Paetzold, J. C. (2024). Topograph: An efficient Graph-Based Framework for Strictly Topology Preserving Image Segmentation. arXiv preprint arXiv:2411.03228.

[2] Berger, A. H., Lux, L., Stucki N, Bürgin, V., Shit S., Banaszak A., Rueckert D., Bauer U., Paetzold J. C. (2024) Topologically faithful multi-class segmentation in medical images. International Conference on Medical Image Computing and Computer-Assisted Intervention.

[3] Stucki, N., Paetzold, J. C., Shit, S., Menze, B., & Bauer, U. (2023, July). Topologically faithful image segmentation via induced matching of persistence barcodes. In International Conference on Machine Learning (pp. 32698-32727). PMLR.

[4] Stucki, N., Bürgin, V., Paetzold, J. C., & Bauer, U. (2024). Efficient Betti Matching Enables Topology-Aware 3D Segmentation via Persistent Homology. arXiv preprint arXiv:2407.04683.

[5] Bauer, U., Schoenlieb, CB., Wardetzky, M. (2010). Total variation meets topological persistence: A first encounter. AIP Conference Proceedings

<br/>

