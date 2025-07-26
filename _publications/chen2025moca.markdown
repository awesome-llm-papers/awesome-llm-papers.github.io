---
layout: publication
title: 'Moca: Modality-aware Continual Pre-training Makes Better Bidirectional Multimodal
  Embeddings'
authors: Haonan Chen, Hong Liu, Yuping Luo, Liang Wang, Nan Yang, Furu Wei, Zhicheng
  Dou
conference: No Venue
year: 2025
bibkey: chen2025moca
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.23115'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Chen et al.
---
Multimodal embedding models, built upon causal Vision Language Models (VLMs), have shown promise in various tasks. However, current approaches face three key limitations: the use of causal attention in VLM backbones is suboptimal for embedding tasks; scalability issues due to reliance on high-quality labeled paired data for contrastive learning; and limited diversity in training objectives and data. To address these issues, we propose MoCa, a two-stage framework for transforming pre-trained VLMs into effective bidirectional multimodal embedding models. The first stage, Modality-aware Continual Pre-training, introduces a joint reconstruction objective that simultaneously denoises interleaved text and image inputs, enhancing bidirectional context-aware reasoning. The second stage, Heterogeneous Contrastive Fine-tuning, leverages diverse, semantically rich multimodal data beyond simple image-caption pairs to enhance generalization and alignment. Our method addresses the stated limitations by introducing bidirectional attention through continual pre-training, scaling effectively with massive unlabeled datasets via joint reconstruction objectives, and utilizing diverse multimodal data for enhanced representation robustness. Experiments demonstrate that MoCa consistently improves performance across MMEB and ViDoRe-v2 benchmarks, achieving new state-of-the-art results, and exhibits strong scalability with both model size and training data on MMEB.

https://huggingface.co/discussions/paper/6863495a588cea0da970c8ac