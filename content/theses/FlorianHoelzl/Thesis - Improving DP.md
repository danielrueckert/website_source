---
title: "MSc Thesis: Leveraging Differential Privacy to Learn General and Robust Deep Learning Models"
date: "2024-07-17"
authors: ["FlorianHoelzl"]
---

## Description
Deep learning aims at learning general representations of data allowing for downstream tasks such as classification, regression or generation of new data. In practice, however, there are no formal guarantees to what a model learns, resulting in unwanted memorisation of input data and leaking of private information. Differential privacy (DP) is the gold standard of privacy-preserving deep learning, offering a formal guarantee for protecting sensitive information and thus as a consequence learning general representations. Privacy in deep learning, however, still comes at a high privacy-utility trade-off that restricts the practical usability of models trained under DP [1]. We, as researchers, try to solve this issue by looking into learning theory and by developing novel approaches that allow DP networks to challenge non-private approaches.

The privacy-utility trade-off of DP at tight privacy bounds is a main reason that keeps DP from being used in practical application. The work aims at improving the substantially worse prediction performance when training with DP-SGD. There has been an increasing focus in recent research on mitigating the bias introduced by gradient clipping and the destructive impact of noise during convergence [2, 3]. The first work package focuses on reimplementing a baseline approach from literature in order to find a suitable quantitative set of metrics [4, 5] to analyse the impact of adaptive approaches on optimisation in comparison to standard SGD and DP-SGD  [6, 7, 8, 9, 10, 11]. In the second work package, we will further include more approaches from current literature and use the previously identified metrics to evaluate and compare them based on their impact on learning general and private representations. In a third work package, this will ideally allow for identifying key factors for improving optimisation under DP, correspondingly improving current training regimes and reaching performance similar to non-private approaches.

If successful, this work will give a new perspective on the deep learning optimisation and allow for establishing DP as a go to approach in practice to learn general and accurate deep learning models.

## Your qualifications
We are looking for a highly motivated Master’s student in Computer Science, Physics, Engineering or Mathematics. You will establish a comprehensive pipeline in PyTorch or JAX to evaluate the model sparsity and changing privacy-parameters on different benchmark datasets for models trained under DP. You will be working at the institute for AI in Medicine, at the Privacy-Preserving and Trustworthy Machine Learning Group. Importantly, we aim to publish the results of this work, with you, in a follow up study at a high-impact deep learning conference or in an academic journal.
- Strong motivation and interest in deep learning and learning theory.
- Advanced programming skills in Python and a common DL framework (PyTorch, Tensorflow, JAX).
- Independent working style with strong interest in teamwork and methodic research.

## What we offer
- An exciting state-of-the-art research project with many possibilities to bring in your own ideas.
- Close supervision and access to the necessary computer hardware.
- The chance to work in a team of highly qualified experts in image processing, computer vision and deep learning.

## References
1. Monir et al. (2024). A Review of Adaptive Techniques and Data Management Issues in DP-SGD. IEEE 2024.
2. Xiao et al. (2023). A Theory to Instruct Differentially-Private Learning via Clipping Bias Reduction. IEEE 2023.
3. Watson et al. (2023). Inference and Interference: The Role of Clipping, Pruning and Loss Landscapes in Differentially Private Stochastic Gradient Descent. ArXiv, abs/2311.06839.
4. https://en.wikipedia.org/wiki/Total_variation_denoising
5. Watson et al. (2023). Inference and Interference: The Role of Clipping, Pruning and Loss Landscapes in Differentially Private Stochastic Gradient Descent. ArXiv, abs/2311.06839.
6. Andrew et al. (2019). Differentially Private Learning with Adaptive Clipping. NeurIPS 2021.
7. Esipova et al. (2023). Disparate Impact in Differential Privacy from Gradient Misalignment. ICLR 2023.
8. Knolle et al. (2023). Bias-Aware Minimisation: Understanding and Mitigating Estimator Bias in Private SGD. TPDP 2023.
9. Tang et al. (2023). DP-AdamBC: Your DP-Adam Is Actually DP-SGD (Unless You Apply Bias Correction). AAAI 2024.
10. Chilukoti et al. (2023). Auto DP-SGD: Dual Improvements of Privacy and Accuracy via Automatic Clipping Threshold and Noise Multiplier Estimation. ArXiv, abs/2312.02400.
11. Xiao et al. (2023). Geometry of Sensitivity: Twice Sampling and Hybrid Clipping in Differential Privacy with Optimal Gaussian Noise and Application to Deep Learning. ACM CCS 2023.