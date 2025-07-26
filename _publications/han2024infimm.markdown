---
layout: publication
title: 'Infimm-webmath-40b: Advancing Multimodal Pre-training For Enhanced Mathematical
  Reasoning'
authors: Xiaotian Han, Yiren Jian, Xuefeng Hu, Haogeng Liu, Yiqi Wang, Qihang Fan,
  Yuang Ai, Huaibo Huang, Ran He, Zhenheng Yang, Quanzeng You
conference: No Venue
year: 2024
bibkey: han2024infimm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.12568'}]
tags: ["Training Techniques"]
short_authors: Han et al.
---
Pre-training on large-scale, high-quality datasets is crucial for enhancing the reasoning capabilities of Large Language Models (LLMs), especially in specialized domains such as mathematics. Despite the recognized importance, the Multimodal LLMs (MLLMs) field currently lacks a comprehensive open-source pre-training dataset specifically designed for mathematical reasoning. To address this gap, we introduce InfiMM-WebMath-40B, a high-quality dataset of interleaved image-text documents. It comprises 24 million web pages, 85 million associated image URLs, and 40 billion text tokens, all meticulously extracted and filtered from CommonCrawl. We provide a detailed overview of our data collection and processing pipeline. To demonstrate the robustness of InfiMM-WebMath-40B, we conducted evaluations in both text-only and multimodal settings. Our evaluations on text-only benchmarks show that, despite utilizing only 40 billion tokens, our dataset significantly enhances the performance of our 1.3B model, delivering results comparable to DeepSeekMath-1.3B, which uses 120 billion tokens for the same model size. Nevertheless, with the introduction of our multi-modal math pre-training dataset, our models set a new state-of-the-art among open-source models on multi-modal math benchmarks such as MathVerse and We-Math. We release our data at https://huggingface.co/datasets/Infi-MM/InfiMM-WebMath-40B.

https://huggingface.co/discussions/paper/66ecd8f99cbe3098580d1a76