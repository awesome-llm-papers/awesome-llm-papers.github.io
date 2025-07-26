---
layout: publication
title: Autoregressive Semantic Visual Reconstruction Helps Vlms Understand Better
authors: Dianyi Wang, Wei Song, Yikun Wang, Siyuan Wang, Kaicheng Yu, Zhongyu Wei,
  Jiaqi Wang
conference: No Venue
year: 2025
bibkey: wang2025autoregressive
additional_links: [{name: Code, url: 'https://github.com/AlenjandroWang/ASVR'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6848fff842e4f9106973f328'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.09040'}]
tags: ["Has Code", "Tools"]
short_authors: Wang et al.
---
Typical large vision-language models (LVLMs) apply autoregressive supervision solely to textual sequences, without fully incorporating the visual modality into the learning process. This results in three key limitations: (1) an inability to utilize images without accompanying captions, (2) the risk that captions omit critical visual details, and (3) the challenge that certain vision-centric content cannot be adequately conveyed through text. As a result, current LVLMs often prioritize vision-to-language alignment while potentially overlooking fine-grained visual information. While some prior works have explored autoregressive image generation, effectively leveraging autoregressive visual supervision to enhance image understanding remains an open challenge. In this paper, we introduce Autoregressive Semantic Visual Reconstruction (ASVR), which enables joint learning of visual and textual modalities within a unified autoregressive framework. We show that autoregressively reconstructing the raw visual appearance of images does not enhance and may even impair multimodal understanding. In contrast, autoregressively reconstructing the semantic representation of images consistently improves comprehension. Notably, we find that even when models are given continuous image features as input, they can effectively reconstruct discrete semantic tokens, resulting in stable and consistent improvements across a wide range of multimodal understanding benchmarks. Our approach delivers significant performance gains across varying data scales (556k-2M) and types of LLM bacbones. Specifically, ASVR improves LLaVA-1.5 by 5% in average scores across 14 multimodal benchmarks. The code is available at https://github.com/AlenjandroWang/ASVR.

https://huggingface.co/discussions/paper/6848fff842e4f9106973f328