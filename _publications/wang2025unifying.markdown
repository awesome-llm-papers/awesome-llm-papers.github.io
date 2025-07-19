---
layout: publication
title: 'Unifying Biomedical Vision-language Expertise: Towards A Generalist Foundation
  Model Via Multi-clip Knowledge Distillation'
authors: Wang et al.
conference: Nature Medicine
year: 2025
bibkey: wang2025unifying
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.22567'}]
tags: [RAG, Training Techniques, Distillation, Evaluation, Efficiency And Optimization,
  Reinforcement Learning, Security, Multimodal Models, Datasets]
---
CLIP models pretrained on natural images with billion-scale image-text pairs have demonstrated impressive capabilities in zero-shot classification, cross-modal retrieval, and open-ended visual answering. However, transferring this success to biomedicine is hindered by the scarcity of large-scale biomedical image-text corpora, the heterogeneity of image modalities, and fragmented data standards across institutions. These limitations hinder the development of a unified and generalizable biomedical foundation model trained from scratch. To overcome this, we introduce MMKD-CLIP, a generalist biomedical foundation model developed via Multiple Medical CLIP Knowledge Distillation. Rather than relying on billion-scale raw data, MMKD-CLIP distills knowledge from nine state-of-the-art domain-specific or generalist biomedical CLIP models, each pretrained on millions of biomedical image-text pairs. Our two-stage training pipeline first performs CLIP-style pretraining on over 2.9 million biomedical image-text pairs from 26 image modalities, followed by feature-level distillation using over 19.2 million feature pairs extracted from teacher models. We evaluate MMKD-CLIP on 58 diverse biomedical datasets, encompassing over 10.8 million biomedical images across nine image modalities. The evaluation spans six core task types: zero-shot classification, linear probing, cross-modal retrieval, visual question answering, survival prediction, and cancer diagnosis. MMKD-CLIP consistently outperforms all teacher models while demonstrating remarkable robustness and generalization across image domains and task settings. These results underscore that multi-teacher knowledge distillation is a scalable and effective paradigm for building high-performing biomedical foundation models under the practical constraints of real-world data availability.