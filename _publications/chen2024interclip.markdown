---
layout: publication
title: 'Interclip-mep: Interactive CLIP And Memory-enhanced Predictor For Multi-modal
  Sarcasm Detection'
authors: Chen et al.
conference: Proceedings of the 29th ACM International Conference on Multimedia
year: 2024
bibkey: chen2024interclip
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.16464'}]
tags: [Training Techniques, Evaluation, Reinforcement Learning, Multimodal Models,
  Datasets]
---
Sarcasm in social media, often expressed through text-image combinations,
poses challenges for sentiment analysis and intention mining. Current
multi-modal sarcasm detection methods have been demonstrated to overly rely on
spurious cues within the textual modality, revealing a limited ability to
genuinely identify sarcasm through nuanced text-image interactions. To solve
this problem, we propose InterCLIP-MEP, which introduces Interactive CLIP
(InterCLIP) with an efficient training strategy to extract enriched text-image
representations by embedding cross-modal information directly into each
encoder. Additionally, we design a Memory-Enhanced Predictor (MEP) with a
dynamic dual-channel memory that stores valuable test sample knowledge during
inference, acting as a non-parametric classifier for robust sarcasm
recognition. Experiments on two benchmarks demonstrate that InterCLIP-MEP
achieves state-of-the-art performance, with significant accuracy and F1 score
improvements on MMSD and MMSD2.0. Our code is available at
https://github.com/CoderChen01/InterCLIP-MEP.