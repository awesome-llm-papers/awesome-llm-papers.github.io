---
layout: publication
title: Improved Baselines With Visual Instruction Tuning
authors: Liu et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: liu2023improved
citations: 311
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.03744'}]
tags: [RAG, Training Techniques, Prompting, CVPR, Evaluation, Multimodal Models, Datasets]
---
Large multimodal models (LMM) have recently shown encouraging progress with
visual instruction tuning. In this note, we show that the fully-connected
vision-language cross-modal connector in LLaVA is surprisingly powerful and
data-efficient. With simple modifications to LLaVA, namely, using
CLIP-ViT-L-336px with an MLP projection and adding academic-task-oriented VQA
data with simple response formatting prompts, we establish stronger baselines
that achieve state-of-the-art across 11 benchmarks. Our final 13B checkpoint
uses merely 1.2M publicly available data, and finishes full training in ~1 day
on a single 8-A100 node. We hope this can make state-of-the-art LMM research
more accessible. Code and model will be publicly available.