---
title: "MSc Thesis: Medial axis-based segmentation loss"
date: 2024-11-18
authors: ["AlinaDima"]
---
### Description

**Image segmentation** seeks to classify individual pixels in an image into semantic classes, such as e.g. the organs in a CT scan. State-of-the-art approaches to image segmentation [5], while very accurate, have limitations in terms of topological correctness. Topological losses are being investigated to overcome these challenges; for example, CL-Dice [4] introduced a loss based on a differentiable soft skeleton for vessel segmentation. In this work we seek to extend this approach to more complex objects, using the medial axis.

The **medial axis** refers to the set of points inside a shape that are equidistant from at least two boundary points of the shape. It can be thought of as a skeletal representation of the shape, which simplifies its structure while preserving essential geometric and topological properties. Approximating the medial axis efficiently and robustly is an active topic of research [1, 2, 3].

In this project you will implement in Python / adapt from other frameworks the medial axis computation and evaluate its feasibility as a loss in a segmentation problem. You will be working in a state-of-the-art research project with opportunities to bring in you own research ideas. We are looking for a highly motivated student with a **solid background in computer graphics** and experience in **C++**, in addition to experience in **PyTorch**. We will provide access to necessary hardware.

<br/>

### **How to apply**

Please send your CV and transcript to Alina Dima (alina.dima@tum.de) and Suprosanna Shit (suprosanna.shit@uzh.ch) using the subject “**MSc Thesis: Medial axis-based segmentation loss”**. 

Please also include brief summaries of your prior deep learning projects (including your contributions to the project and the used framework) and, if available, provide links to the codebases (e.g., your GitHub profile).

<br/>

### References

[1] Yan, Y., Letscher, D., & Ju, T. (2018). Voxel cores: Efficient, robust, and provably good approximation of 3d medial axes. *ACM Transactions on Graphics (TOG)*, *37*(4), 1-13.

[2] Pepe, A., Schussnig, R., Li, J., Gsaxner, C., Schmalstieg, D., & Egger, J. (2024). Deep Medial Voxels: Learned Medial Axis Approximations for Anatomical Shape Modeling. *arXiv preprint arXiv:2403.11790*.

[3] Wang, N., Huang, H., Song, S., Wang, B., Wang, W., & Guo, X. (2024). MATTopo: Topology-preserving Medial Axis Transform with Restricted Power Diagram. *arXiv preprint arXiv:2403.18761*.

[4] Shit, S., Paetzold, J. C., Sekuboyina, A., Ezhov, I., Unger, A., Zhylka, A., ... & Menze, B. H. (2021). clDice-a novel topology-preserving  loss function for tubular structure segmentation. In *Proceedings of the IEEE/CVF conference on computer vision and pattern recognition* (pp. 16560-16569).

[5] Isensee, F., Jaeger, P. F., Kohl, S. A., Petersen, J., & Maier-Hein, K. H. (2021). nnU-Net: a self-configuring method for deep learning-based biomedical image segmentation. *Nature methods*, *18*(2), 203-211.