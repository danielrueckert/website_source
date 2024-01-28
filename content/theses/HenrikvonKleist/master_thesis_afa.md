---
title: "MSc Thesis: Semi-offline Reinforcement Learning for Active Feature Acquisition"
date: 2024-01-10
authors: ["HenrikvonKleist"]
---

In this Master thesis, we aim to develop novel _semi-offline reinforcement learning (RL)_ methods for the task of _active feature acquisition (AFA)_ and apply these methods to the medical problem of _sepsis diagnosis_.  

###### What is active feature acquisition (AFA)?

Classification methods often assume input features are available at no cost. However, in domains like healthcare, where acquiring features could be expensive or harmful, it is necessary to balance a feature’s acquisition cost against its predictive value. AFA addresses this problem by training two AI systems: i) the "AFA agent", a reinforcement learning agent tasked with determining which features should be acquired, and ii) a classification model that performs a diagnosis based on the acquired feature set.  

###### What is semi-offline reinforcement learning (RL)?

We only have access to historical datasets where a doctor decided on the feature acquisitions. We would like to, however, answer questions about what would have happened if the AFA agent had decided on the feature acquisitions. This requires counterfactual reasoning and thus methods from causal inference/dynamic treatment regimes/offline RL. In recent work [1,2], we showed that one can achieve significant data efficiency benefits in AFA settings compared to regular offline RL settings by simulating additional data points within a novel semi-offline RL framework.  We now want to extend this semi-offline RL framework which is currently only used for agent evaluation to also handle optimization of agents. 

###### How can this be used for sepsis prediction?

Sepsis is caused by an infection and can cause up to 35% of in-hospital deaths [3]. Early detection is thus crucial and can increase the chance of survival significantly. Prediction models for the task of sepsis prediction have already been successfully included in hospital settings and have shown to reduce the mortality due to sepsis [4]. We aim to augment this prediction process, by additionally recommending how to schedule blood tests, needed for accurate sepsis prediction using AFA. Additionally, we plan to extend this research to applications in hematology and Alzheimer's research. 

<br/>

## Your qualifications:

We are looking for a highly motivated Master’s student in Bioinformatics, Computer Science, Physics, Engineering or Mathematics. Your task is to extend the existing AFA codebase to include the optimization of RL agent and to apply it to novel datasets. You will be working together with Henrik, a PhD student supervised by Prof. Daniel Rückert at TUM and Carsten Marr at Helmholtz Munich. Importantly, we aim to publish the results of this work, with you, at a high-impact machine learning conference or in an academic journal.

Required Features: 

- Strong motivation and interest in machine learning, causal inference, and reinforcement learning.

- Advanced programming skills in Python.

- Strong interest in teamwork and interdisciplinary research.

<br/>

## What we offer:

-   An exciting research project in the field of causal inference and reinforcement learning 
-   The chance to bring in your own ideas for methods development or application.
-   The chance to work in a team of highly qualified experts in AI and healthcare/ biology applications.

<br/>

## Milestones

We plan to implement the following milestones: 

- Week 0: Choosing the optimization approach: Model-based RL, Actor-critic methods or policy-gradient methods

- Week 0-2: Getting familiar with AFA, semi-offline RL and the existing AFA library 
- Week 2-3: Getting familiar with state-of-the-art AFA literature that applies the chosen optimization approach 
- Week 3-4: Mathematical adaptation of the chosen optimization approach to semi-offline RL 
- Week 4-12: Implementation 
- Week 12: Mid-term evaluation
- Week 12-18: Testing on sepsis data
- Week 20: Submission of research manuscript to conference
- Week 22: First thesis draft ready
- Week 24: Final thesis submission



## How to apply:

Just send an email to henrik.vonkleist@helmholtz-munich.de with a short CV and your grade report. 

## References:

[1] von Kleist, H., Zamanian, A., Shpitser, I., & Ahmidi, N. (2023). Evaluation of Active Feature Acquisition Methods for Time-varying Feature Settings. *arXiv preprint arXiv:2312.01530*.

[2] von Kleist, H., Zamanian, A., Shpitser, I., & Ahmidi, N. (2023). Evaluation of Active Feature Acquisition Methods for Static Feature Settings. *arXiv preprint arXiv:2312.03619*.

[3] Rhee, C., Jones, T. M., Hamad, Y., Pande, A., Varon, J., O’Brien, C., ... & Klompas, M. (2019). Prevalence, underlying causes, and preventability of sepsis-associated mortality in US acute care hospitals. *JAMA network open*, *2*(2), e187571-e187571.

[4] Adams, R., Henry, K. E., Sridharan, A., Soleimani, H., Zhan, A., Rawat, N., ... & Saria, S. (2022). Prospective, multi-site study of patient outcomes after implementation of the TREWS machine learning-based early warning system for sepsis. *Nature medicine*, *28*(7), 1455-1460.

