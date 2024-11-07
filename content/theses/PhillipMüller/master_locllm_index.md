---
title: "MSc Thesis: Making LLMs Localize Objects"
date: 2024-11-05
authors: ["PhilipMueller"]
---
**TL;DR**: We want to integrate specialized localization components into LLM-based VLMs to improve their localization capabilities and overall performance on localized tasks such as object detection, referring expression generation.

<br/>

### Description

**Vision-Language Models (VLMs)** integrate computer vision and natural language processing
approaches to handle both images and text in a single model. Typical tasks include image captioning (i.e., predicting textual descriptions for images) and visual question answering (i.e., answering questions related to images). 

State-of-the-art VLMs like Llama 3.2 **[1]** or LLaVa **[2,3]** integrate pre-trained image encoders into **LLMs** using adapter layers that project image features into the LLM token space. Utilizing the concepts learned by LLMs, these models showcase strong results on vision-language tasks.

However, these models are quite limited in their **localization** capabilities. While some works **[4-7]** use coordinate tokens to predict bounding boxes, the LLMs are not specialized for localization tasks, thus typically underperforming specialized models on localization tasks such as **object detection and referring expression generation**. Recently, some works have tried integrating localization into VLMs **[8-11]**. We want to build on these works and integrate specialized localization components into LLM-based VLMs.

We will be adapting LLaVa **[2]**-style VLMs with state-of-the-art LLMs and integrating DETR **[12]**-style object detectors. Note that this work focuses on natural images but may be evaluated later on medical tasks.

<br/>

### Your qualifications

We are looking for a highly motivated Master’s student in Computer Science, Physics, Engineering, Mathematics, or a related field. 

You will establish a new model and training pipeline in PyTorch and evaluate the model on several benchmarks. 

You will work at the Institute for AI in Medicine at TU Munich. Importantly, we aim to publish the results of this work with you in a follow-up study at a high-impact computer vision conference or in an academic journal (e.g., CVPR, ICCV, ...) .

1. Strong motivation and interest in machine learning and computer vision.
2. Advanced programming skills in Python and a common DL framework (PyTorch, Tensorflow, JAX), preferably PyTorch.
3. Independent working style with a strong interest in teamwork and methodic research.
4. (Optional) Prior experience with LLMs or object detection is a plus but not required.

<br/>

### What we offer

- An exciting state-of-the-art research project with many possibilities to bring in your own ideas.
- Close supervision and access to the necessary computer hardware.
- The chance to work in a team of highly qualified experts in machine learning, computer vision, and deep learning.
- The chance to publish the work in high-impact venues or journals.

<br/>

### **How to apply**

Please send your CV and transcript to Philip Müller (philip.j.mueller@tum.de) using the subject “**MSc Thesis: Making LLMs Localize Objects”**. 

Please also include brief summaries of your prior deep learning projects (including your contributions to the project and the used framework) and, if available, provide links to the codebases (e.g., your GitHub profile).

<br/>

### References

[1] Meta. Llama 3.2: Revolutionizing edge AI and vision with open, customizable models. 2024 (https://ai.meta.com/blog/llama-3-2-connect-2024-vision-edge-mobile-devices/)

[2] Liu et al. Visual Instruction Tuning. NeurIPS 2023 (https://arxiv.org/abs/2304.08485)

[3] Liu et al. Improved Baselines with Visual Instruction Tuning. CVPR 2024 (https://arxiv.org/abs/2310.03744)

[4] Chen et al. Pix2seq: A Language Modeling Framework for Object Detection. ICLR 2022 (https://arxiv.org/abs/2109.10852)

[5] Yang et al. UniTAB: Unifying Text and Box Outputs for Grounded Vision-Language Modeling. ECCV 2022 (https://arxiv.org/abs/2111.12085)

[6] Peng et al. Kosmos-2: Grounding Multimodal Large Language Models to the World. ICLR 2023 (https://arxiv.org/abs/2306.14824)

[7] Bannur et al. MAIRA-2: Grounded Radiology Report Generation. 2024 (https://arxiv.org/abs/2406.04449)

[8] Lai et al. LISA: Reasoning Segmentation via Large Language Model. CVPR 2024 (https://arxiv.org/abs/2308.00692)

[9] Rasheed et al. GLaMM: Pixel Grounding Large Multimodal Model. CVPR 2024 (https://arxiv.org/abs/2311.03356)

[10] Zhang et al. PSALM: Pixelwise SegmentAtion with Large Multi-Modal Model. 2024 (https://arxiv.org/abs/2403.14598)

[11] Müller et al. ChEX: Interactive Localization and Region Description in Chest X-rays. ECCV 2024 (https://arxiv.org/abs/2404.15770)

[12] Carion et al. End-to-End Object Detection with Transformers. ECCV 2020 (https://arxiv.org/abs/2005.12872)


<br/>
