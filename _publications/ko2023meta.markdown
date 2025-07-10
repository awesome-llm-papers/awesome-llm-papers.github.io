---
layout: publication
title: 'MELTR: Meta Loss Transformer For Learning To Fine-tune Video Foundation Models'
authors: Dohwan Ko et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
citations: 16
bibkey: ko2023meta
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.13009'}, {name: Code,
    url: 'https://github.com/mlvlab/MELTR'}]
tags: [Has Code, Model Architecture, Transformer, Fine-Tuning, RAG, Tools, Reinforcement
    Learning, Efficiency and Optimization, Training Techniques, Evaluation]
---
Foundation models have shown outstanding performance and generalization
capabilities across domains. Since most studies on foundation models mainly
focus on the pretraining phase, a naive strategy to minimize a single
task-specific loss is adopted for fine-tuning. However, such fine-tuning
methods do not fully leverage other losses that are potentially beneficial for
the target task. Therefore, we propose MEta Loss TRansformer (MELTR), a plug-in
module that automatically and non-linearly combines various loss functions to
aid learning the target task via auxiliary learning. We formulate the auxiliary
learning as a bi-level optimization problem and present an efficient
optimization algorithm based on Approximate Implicit Differentiation (AID). For
evaluation, we apply our framework to various video foundation models (UniVL,
Violet and All-in-one), and show significant performance gain on all four
downstream tasks: text-to-video retrieval, video question answering, video
captioning, and multi-modal sentiment analysis. Our qualitative analyses
demonstrate that MELTR adequately `transforms' individual loss functions and
`melts' them into an effective unified loss. Code is available at
https://github.com/mlvlab/MELTR.