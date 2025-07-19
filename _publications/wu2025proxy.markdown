---
layout: publication
title: 'Proxy-tuning: Tailoring Multimodal Autoregressive Models For Subject-driven
  Image Generation'
authors: Wu et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: wu2025proxy
citations: 1132
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.10125'}]
tags: [RAG, GPT, Prompting, CVPR, Transformer, Model Architecture, Language Modeling,
  Reinforcement Learning, Multimodal Models, Merging]
---
Multimodal autoregressive (AR) models, based on next-token prediction and
transformer architecture, have demonstrated remarkable capabilities in various
multimodal tasks including text-to-image (T2I) generation. Despite their strong
performance in general T2I tasks, our research reveals that these models
initially struggle with subject-driven image generation compared to dominant
diffusion models. To address this limitation, we introduce Proxy-Tuning,
leveraging diffusion models to enhance AR models' capabilities in
subject-specific image generation. Our method reveals a striking weak-to-strong
phenomenon: fine-tuned AR models consistently outperform their diffusion model
supervisors in both subject fidelity and prompt adherence. We analyze this
performance shift and identify scenarios where AR models excel, particularly in
multi-subject compositions and contextual understanding. This work not only
demonstrates impressive results in subject-driven AR image generation, but also
unveils the potential of weak-to-strong generalization in the image generation
domain, contributing to a deeper understanding of different architectures'
strengths and limitations.