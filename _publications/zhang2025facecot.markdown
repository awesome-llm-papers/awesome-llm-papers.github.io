---
layout: publication
title: 'Facecot: A Benchmark Dataset For Face Anti-spoofing With Chain-of-thought
  Reasoning'
authors: Zhang et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: zhang2025facecot
citations: 134
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.01783'}]
tags: [Interpretability And Explainability, RAG, Agentic, Evaluation, CVPR, Reinforcement
    Learning, Security, Multimodal Models, Datasets]
---
Face Anti-Spoofing (FAS) typically depends on a single visual modality when defending against presentation attacks such as print attacks, screen replays, and 3D masks, resulting in limited generalization across devices, environments, and attack types. Meanwhile, Multimodal Large Language Models (MLLMs) have recently achieved breakthroughs in image-text understanding and semantic reasoning, suggesting that integrating visual and linguistic co-inference into FAS can substantially improve both robustness and interpretability. However, the lack of a high-quality vision-language multimodal dataset has been a critical bottleneck. To address this, we introduce FaceCoT (Face Chain-of-Thought), the first large-scale Visual Question Answering (VQA) dataset tailored for FAS. FaceCoT covers 14 spoofing attack types and enriches model learning with high-quality CoT VQA annotations. Meanwhile, we develop a caption model refined via reinforcement learning to expand the dataset and enhance annotation quality. Furthermore, we introduce a CoT-Enhanced Progressive Learning (CEPL) strategy to better leverage the CoT data and boost model performance on FAS tasks. Extensive experiments demonstrate that models trained with FaceCoT and CEPL outperform state-of-the-art methods on multiple benchmark datasets.