---
layout: publication
title: 'Qoq-med: Building Multimodal Clinical Foundation Models With Domain-aware
  GRPO Training'
authors: Dai et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2025
bibkey: dai2025qoq
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.00711'}]
tags: [RAG, Training Techniques, Alt, Efficiency And Optimization, Reinforcement Learning,
  Multimodal Models, AAAI]
---
Clinical decision-making routinely demands reasoning over heterogeneous data, yet existing multimodal language models (MLLMs) remain largely vision-centric and fail to generalize across clinical specialties. To bridge this gap, we introduce QoQ-Med-7B/32B, the first open generalist clinical foundation model that jointly reasons across medical images, time-series signals, and text reports. QoQ-Med is trained with Domain-aware Relative Policy Optimization (DRPO), a novel reinforcement-learning objective that hierarchically scales normalized rewards according to domain rarity and modality difficulty, mitigating performance imbalance caused by skewed clinical data distributions. Trained on 2.61 million instruction tuning pairs spanning 9 clinical domains, we show that DRPO training boosts diagnostic performance by 43% in macro-F1 on average across all visual domains as compared to other critic-free training methods like GRPO. Furthermore, with QoQ-Med trained on intensive segmentation data, it is able to highlight salient regions related to the diagnosis, with an IoU 10x higher than open models while reaching the performance of OpenAI o4-mini. To foster reproducibility and downstream research, we release (i) the full model weights, (ii) the modular training pipeline, and (iii) all intermediate reasoning traces at https://github.com/DDVD233/QoQ_Med.