---
layout: publication
title: 'LORE: Lagrangian-optimized Robust Embeddings For Visual Encoders'
authors: Khodabandeh et al.
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2025
bibkey: khodabandeh2025lore
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.18884'}]
tags: [Interpretability And Explainability, ICCV, Training Techniques, Tools, Efficiency
    And Optimization, Reinforcement Learning, Security, Fine Tuning]
---
Visual encoders have become fundamental components in modern computer vision pipelines. However, ensuring robustness against adversarial perturbations remains a critical challenge. Recent efforts have explored both supervised and unsupervised adversarial fine-tuning strategies. We identify two key limitations in these approaches: (i) they often suffer from instability, especially during the early stages of fine-tuning, resulting in suboptimal convergence and degraded performance on clean data, and (ii) they exhibit a suboptimal trade-off between robustness and clean data accuracy, hindering the simultaneous optimization of both objectives. To overcome these challenges, we propose Lagrangian-Optimized Robust Embeddings (LORE), a novel unsupervised adversarial fine-tuning framework. LORE utilizes constrained optimization, which offers a principled approach to balancing competing goals, such as improving robustness while preserving nominal performance. By enforcing embedding-space proximity constraints, LORE effectively maintains clean data performance throughout adversarial fine-tuning. Extensive experiments show that LORE significantly improves zero-shot adversarial robustness with minimal degradation in clean data accuracy. Furthermore, we demonstrate the effectiveness of the adversarially fine-tuned CLIP image encoder in out-of-distribution generalization and enhancing the interpretability of image embeddings.