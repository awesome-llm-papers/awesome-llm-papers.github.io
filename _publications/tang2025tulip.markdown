---
layout: publication
title: 'TULIP: Towards Unified Language-image Pretraining'
authors: Zineng Tang, Long Lian, Seun Eisape, Xudong Wang, Roei Herzig, Adam Yala,
  Alane Suhr, Trevor Darrell, David M. Chan
conference: No Venue
year: 2025
bibkey: tang2025tulip
additional_links: [{name: Code, url: 'https://tulip-berkeley.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67db7dd424fe67fe45b21ee1'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2503.15485'}]
tags: ["Few-Shot", "Has Code"]
short_authors: Tang et al.
---
Despite the recent success of image-text contrastive models like CLIP and SigLIP, these models often struggle with vision-centric tasks that demand high-fidelity image understanding, such as counting, depth estimation, and fine-grained object recognition. These models, by performing language alignment, tend to prioritize high-level semantics over visual understanding, weakening their image understanding. On the other hand, vision-focused models are great at processing visual information but struggle to understand language, limiting their flexibility for language-driven tasks. In this work, we introduce TULIP, an open-source, drop-in replacement for existing CLIP-like models. Our method leverages generative data augmentation, enhanced image-image and text-text contrastive learning, and image/text reconstruction regularization to learn fine-grained visual features while preserving global semantic alignment. Our approach, scaling to over 1B parameters, outperforms existing state-of-the-art (SOTA) models across multiple benchmarks, establishing a new SOTA zero-shot performance on ImageNet-1K, delivering up to a 2times enhancement over SigLIP on RxRx1 in linear probing for few-shot classification, and improving vision-language models, achieving over 3times higher scores than SigLIP on MMVP. Our code/checkpoints are available at https://tulip-berkeley.github.io

https://huggingface.co/discussions/paper/67db7dd424fe67fe45b21ee1