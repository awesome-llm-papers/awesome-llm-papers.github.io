---
layout: publication
title: Can Llms Deceive CLIP? Benchmarking Adversarial Compositionality Of Pre-trained
  Multimodal Representation Via Text Updates
authors: Ahn et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: ahn2025can
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.22943'}]
tags: [RAG, Training Techniques, CVPR, Evaluation, Security, Fine Tuning, Multimodal
    Models, Datasets]
---
While pre-trained multimodal representations (e.g., CLIP) have shown impressive capabilities, they exhibit significant compositional vulnerabilities leading to counterintuitive judgments. We introduce Multimodal Adversarial Compositionality (MAC), a benchmark that leverages large language models (LLMs) to generate deceptive text samples to exploit these vulnerabilities across different modalities and evaluates them through both sample-wise attack success rate and group-wise entropy-based diversity. To improve zero-shot methods, we propose a self-training approach that leverages rejection-sampling fine-tuning with diversity-promoting filtering, which enhances both attack success rate and sample diversity. Using smaller language models like Llama-3.1-8B, our approach demonstrates superior performance in revealing compositional vulnerabilities across various multimodal representations, including images, videos, and audios.