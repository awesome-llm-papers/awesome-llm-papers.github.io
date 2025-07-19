---
layout: publication
title: 'Inattention: Linear Context Scaling For Transformers'
authors: Eisner Joseph
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: eisner2024inattention
citations: 478
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.07063'}]
tags: [Training Techniques, Attention Mechanism, CVPR, Evaluation, Transformer, Model
    Architecture, Efficiency And Optimization, Reinforcement Learning, Fine Tuning,
  Datasets]
---
VRAM requirements for transformer models scale quadratically with context
length due to the self-attention mechanism. In this paper we modify the
decoder-only transformer, replacing self-attention with InAttention, which
scales linearly with context length during inference by having tokens attend
only to initial states. Benchmarking shows that InAttention significantly
reduces VRAM usage during inference, enabling handling of long sequences on
consumer GPUs. We corroborate that fine-tuning extends context length
efficiently, improving performance on long sequences without high training
costs. InAttention offers a scalable solution for long-range dependencies in
transformer models, paving the way for further optimization.