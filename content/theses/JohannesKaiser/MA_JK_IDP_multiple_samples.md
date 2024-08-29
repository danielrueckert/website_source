---
title: "A Privacy-Preserving Framework for Multi-Entry Medical Datasets"
date: 2024-08-29
authors: [Johannes Kaiser]
---
In this master's thesis, we aim to explore the potential of leveraging multiple data entries per contributor across various medical datasets (ex. Chexpert) while maintaining differential privacy guarantees at the per-contributor level.

In sensitive domains like medicine, protecting the privacy of individuals contributing their data to research (e.g., for training neural networks) is of utmost importance.

Differential privacy [1] (the gold standard for privacy protection in deep learning) ensures that only a quantifiable and limited amount of a contributor's data is exposed as a result of their participation in a study. Commonly, differential privacy with contributor-level guarantees assumes that a database contains only a single entry per contributor. In cases where multiple entries exist for a contributor, the typical approach is to impose a limit on the number of entries and treat each individual as if they had contributed the maximum allowed number.

However, this approach presents two key problems:

1. Limiting the number of entries results in the loss of valuable data, reducing the expressiveness and utility of the remaining dataset.

2. Treating all individuals as if they provided the maximum allowed number of entries imposes unnecessarily strict privacy constraints on those who have contributed fewer entries.

This creates a trade-off between the amount of data discarded and the number of individuals whose data is processed under overly restrictive privacy guarantees.

In this thesis we want to explore a novel approach in employing individual-level differential privacy [2] to (1) use all the available data while (2) providing fitting privacy guarantees for any individual.
By leveraging this approach, we aim to achieve higher performance on medical datasets, improving the diagnostic accuracy while protecting the privacy of the contributors.

<br/>

## Your qualifications:

We are looking for a highly motivated Master’s student in Computer Science, Engineering or Mathematics. Your goal is to extend the existing Pytorch codebase and apply it to novel datasets. Importantly, we aim to publish the results of this work, with you, in a follow up study at a high-impact machine learning conference or in an academic journal.

1. Strong motivation and interest in machine learning.
2. Advanced programming skills in Python.
3. Strong interest in teamwork and interdisciplinary research.

<br/>

## What we offer:

-   An exciting research project with many possibilities to bring in your own ideas.
-   Close supervision and access to state-of-the-art computer hardware.
-   The chance to work in a team of highly qualified experts in machine learning, computer vision, and deep learning.

<br/>

## How to apply:

Just send an email to johannes.kaiser@tum.de, with a short CV and your grade report. I promise to get back to you within days.

<br/>

## References:

[1] Abadi, Martin, et al. "Deep learning with differential privacy." Proceedings of the 2016 ACM SIGSAC conference on computer and communications security. (2016).

[2] Boenisch, Franziska, et al. "Have it your way: Individualized Privacy Assignment for DP-SGD." Advances in Neural Information Processing Systems 36 (2024).
 
<br/>
