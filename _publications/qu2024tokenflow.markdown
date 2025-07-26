---
layout: publication
title: 'Tokenflow: Unified Image Tokenizer For Multimodal Understanding And Generation'
authors: Liao Qu, Huichao Zhang, Yiheng Liu, Xu Wang, Yi Jiang, Yiming Gao, Hu Ye,
  Daniel K. Du, Zehuan Yuan, Xinglong Wu
conference: No Venue
year: 2024
bibkey: qu2024tokenflow
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/675117464af3ce83f1c4368b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.03069'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Qu et al.
---
We present TokenFlow, a novel unified image tokenizer that bridges the long-standing gap between multimodal understanding and generation. Prior research attempt to employ a single reconstruction-targeted Vector Quantization (VQ) encoder for unifying these two tasks. We observe that understanding and generation require fundamentally different granularities of visual information. This leads to a critical trade-off, particularly compromising performance in multimodal understanding tasks. TokenFlow addresses this challenge through an innovative dual-codebook architecture that decouples semantic and pixel-level feature learning while maintaining their alignment via a shared mapping mechanism. This design enables direct access to both high-level semantic representations crucial for understanding tasks and fine-grained visual features essential for generation through shared indices. Our extensive experiments demonstrate TokenFlow's superiority across multiple dimensions. Leveraging TokenFlow, we demonstrate for the first time that discrete visual input can surpass LLaVA-1.5 13B in understanding performance, achieving a 7.2% average improvement. For image reconstruction, we achieve a strong FID score of 0.63 at 384*384 resolution. Moreover, TokenFlow establishes state-of-the-art performance in autoregressive image generation with a GenEval score of 0.55 at 256*256 resolution, achieving comparable results to SDXL.

https://huggingface.co/discussions/paper/675117464af3ce83f1c4368b