---
title: "MSc Thesis: Outperforming CNNs and Transformers on Medical Imaging Tasks with Equivariant Networks"
date: "2024-07-17"
authors: ["FlorianHoelzl"]
---

## Description
Equivariant convolutions are a novel approach that incorporate additional geometric properties of the input domain during the convolution process (i.e. symmetry properties such as rotations and reflections) [1]. This additional inductive bias allows the model to learn more robust and general features from less data, rendering them highly promising for application in the medical domain. So far, however, nobody has investigated how their beneficial characteristics impact the design and scaling of deep learning model architectures.

We have developed a framework for initial investigation of equivariant convolutions and now want to evaluate how their performance can be further increased with larger model sizes and under different training regimes. This work plans to build onto previous highly impactful research on model design, such as the establishment of the EfficientNet architecture and the Chinchilla language model, to create a sound basis for the further consolidation of equivariant convolutions in the broader research landscape [2, 3]. The focus will be to thoroughly analyse and expand a framework for equivariant models already developed at our lab. This includes getting familiar with model architectures in general, the properties of equivariant convolutions and the intersection of the two. Our goal is to develop a family of equivariant model architectures that can be easily adapted to the properties of the used dataset and are able to beat state-of-the-art non-equivariant alternatives [4].

## Your qualifications
We are looking for a highly motivated Master’s student in Computer Science, Physics, Engineering or Mathematics. You will establish a comprehensive pipeline in PyTorch or JAX to evaluate the properties of equivariant models on different benchmark datasets. You will be working at the institute for AI in Medicine, at the Privacy-Preserving and Trustworthy Machine Learning Group. Importantly, we aim to publish the results of this work, with you, in a follow up study at a high-impact deep learning conference or in an academic journal.

- Strong motivation and interest in deep learning and learning theory.
- Advanced programming skills in Python and a common DL framework (PyTorch, Tensorflow, JAX).
- Independent working style with strong interest in teamwork and methodic research.

## What we offer
- An exciting state-of-the-art research project with many possibilities to bring in your own ideas.
- Close supervision and access to the necessary computer hardware.
- The chance to work in a team of highly qualified experts in image processing, computer vision and deep learning.

## References
1. Cohen and Welling (2016). Group Equivariant Convolutions. ICML 2016.
2. Tan and Le (2019). EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks. ICML 2019.
3. Hoffmann et al. (2022). Training Compute-Optimal Large Language Models. ArXiv, abs/2203.15556.
4. Abadi et al. (2016). Deep Learning with Differential Privacy. ACM SIGSAC 2016.