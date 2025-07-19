---
layout: publication
title: Maintain Plasticity In Long-timescale Continual Test-time Adaptation
authors: Wang et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: wang2024maintain
citations: 236
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.20034'}]
tags: [CVPR, Evaluation, Reinforcement Learning, Fine Tuning, Datasets]
---
Continual test-time domain adaptation (CTTA) aims to adjust pre-trained
source models to perform well over time across non-stationary target
environments. While previous methods have made considerable efforts to optimize
the adaptation process, a crucial question remains: can the model adapt to
continually-changing environments with preserved plasticity over a long time?
The plasticity refers to the model's capability to adjust predictions in
response to non-stationary environments continually. In this work, we explore
plasticity, this essential but often overlooked aspect of continual adaptation
to facilitate more sustained adaptation in the long run. First, we observe that
most CTTA methods experience a steady and consistent decline in plasticity
during the long-timescale continual adaptation phase. Moreover, we find that
the loss of plasticity is strongly associated with the change in label flip.
Based on this correlation, we propose a simple yet effective policy, Adaptive
Shrink-Restore (ASR), towards preserving the model's plasticity. In particular,
ASR does the weight re-initialization by the adaptive intervals. The adaptive
interval is determined based on the change in label flipping. Our method is
validated on extensive CTTA benchmarks, achieving excellent performance.