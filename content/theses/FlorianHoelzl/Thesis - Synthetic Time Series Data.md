---
title: "MSc Thesis: Privacy-Preserving Synthetic Time Series Data of Electronic Health Records"
date: "2024-07-17"
authors: ["FlorianHoelzl"]
---

## Description
Anonymizing data means removing or replacing any identifying information from a dataset, such as names or addresses. The aim of anonymization is to protect the privacy of individuals whose data is being collected and processed. However, anonymizing data is not sufficient to guarantee privacy protection. Research has shown that data samples can easily re-identified through a variety of approaches as simply as combining a dataset with other data sources, e.g. publicly available information [1]. This poses a problem for data sharing, especially in highly sensitive domains such as medicine.

Synthetic data allows to generate new examples that preserve the statistical properties of the original data [2]. In a medical use case, synthetic data could be used to generate realistic but entirely artificial medical records. These synthetic medical records can be used for a variety of different purposes, such as augmenting existing datasets or sharing data without revealing any patient information [3].

For the later, however, synthetic data doesn’t per se protect the privacy of individual patients. To achieve privacy preservation, we have to apply additional techniques such as differential privacy [4]. The aim of this project is to evaluate synthetic data generation with differential privacy for medical records of multi-variate time series. You will first evaluate current literature of synthetic data generation for multi-variate time series with varying sequence lengths and irregular time differences [5]. In the second work package, an existing data generation pipeline will be re-evaluated and compared to existing synthetisation approaches on a real-world multiple sclerosis dataset. The data will be used to predict disease activity and help treatment decision making for disease-modifying therapies [6]. To measure the prediction capabilities of the synthetically generated private data, its prediction performance is compared against existing baselines from the original data curated during different time intervals. Furthermore, the addition of synthetic data into the existing training process for increased model robustness will be assessed. The third work package consists of improving the pipeline, especially with regard to conditional sampling, and evaluating it on other publicly available datasets.

## Your qualifications
We are looking for a highly motivated Master’s student in Computer Science, Physics, Engineering or Mathematics. You will establish a comprehensive pipeline in PyTorch or JAX to generate and evaluate synthetic data from a real world medical dataset under differential privacy. You will be working at the institute for AI in Medicine, at the Privacy-Preserving and Trustworthy Machine Learning Group. Importantly, we aim to publish the results of this work, with you, in a follow up study at a high-impact deep learning conference or in an academic journal.
- Strong motivation and interest in deep learning and learning theory.
- Advanced programming skills in Python and a common DL framework (PyTorch, Tensorflow, JAX).
- Independent working style with strong interest in teamwork and methodic research.

## What we offer
- An exciting state-of-the-art research project with many possibilities to bring in your own ideas.
- Close supervision and access to the necessary computer hardware.
- The chance to work in a team of highly qualified experts in image processing, computer vision and deep learning.

## References
1. Narayanan and Shmatikov (2006). How to Break Anonymity of the Netflix Prize Dataset. ArXiv, cs/0610105
2. Jordon et al. (2022). Synthetic Data - what, why and how? ArXiv, abs/2205.03257.
3. Chen et al. (2021). Synthetic Data in Machine Learning for Medicine and Healthcare. Nature Biomedical Engineering 2021.
4. Abadi et al. (2016). Deep Learning with Differential Privacy. ACM SIGSAC 2016.
5. Zhang et al. (2022). Sequential models in the synthetic data vault. ArXiv, abs/2207.14406.
7. Braune et al. (2022). PHREND®—A Real-World Data-Driven Tool Supporting Clinical Decisions to Optimize Treatment in Relapsing-Remitting Multiple Sclerosis. Frontiers in Digital Health 03.2022.