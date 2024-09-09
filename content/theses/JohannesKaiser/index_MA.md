---
title: "MSc Thesis: Laplace Approximation based Evaluation of Model Multiplicity on Medical Imaging Data"
date: 2024-09-09
authors: ["Johannes Kaiser", "Sarah Lockfisch"]
---

In this master thesis we aim to explore the presence of predictive multiplicity in neural networks trained to predict pathologies in medical imaging datasets.
In short, predictive multiplicity describes a phenomenon in which models trained for the same objective and achieving similar measures of predictive performances, such as loss or accuracy, may behave very differently for individual samples [1].
While it is rather difficult and computationally expensive to acquire large sets of trained neural networks (as it requires retraining of the whole model), Laplace approximations allow to train a single model, construct a distribution of weights and sample from this distribution of weights.
A recently proposed Riemannian Laplace Approximation allows to sample weights not only in the vicinity of the initial weights, but also with similar loss.
This allows to generate large sets of model weights with hardly any computational effort [2].
The variance in terms of non-target metrices of these models is strongly underexplored.
This thesis should explore the variance in serveral desiderate metrices (such as fairness, robustness etc.) across the models contained in these sets.
There is evidence, that a large enough set of neural networks is likey to contain models that perform well in the desiderate metrices.
The results of this thesis may lead to the possibility of having fairer machine learning models performing medical diagnosis (for example in chest x-ray evaluation) without any fairness constraints or additional computational effort.

<br/>

## Your qualifications:

We are looking for a highly motivated Master’s student in Computer Science, Engineering or Mathematics. Your goal is to extend the existing Pytorch codebase and apply it to medical imaging datasets. You will be working together with Johannes and Sarah, two Doctoral students at TU Munich under the supervision of Prof. Daniel Rückert. Importantly, this is cutting edge research such that with good results there is the chance to publish the findings at a machine learning conference.

1. Strong motivation and interest in machine learning.
2. Advanced programming skills in Python.
3. Familiarity with deep learning libraries such as pytorch
4. Strong communication skills.

<br/>

## What we offer:

-   An exciting research project with many possibilities to bring in your own ideas.
-   Close supervision and access to state-of-the-art computer hardware.

<br/>

## How to apply:

Just send an email to johannes.kaiser@tum.de, with a short CV and your grade report. We promise to get back to you within days.


<br/>

## References:

[1] Black, Emily, et al. "Model Multiplicity: Opportunities, Concerns, and Solutions" ACM Conference on Fairness, Accountability, and Transparency. (2022)

[2] Bergamin, Federico, et al. "Riemannian Laplace approximations for Bayesian neural networks." Advances in Neural Information Processing Systems 36 (2024).
<br/>
