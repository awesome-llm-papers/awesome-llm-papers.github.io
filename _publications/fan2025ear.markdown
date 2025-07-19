---
layout: publication
title: 'EAR: Erasing Concepts From Unified Autoregressive Models'
authors: Fan et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: fan2025ear
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.20151'}]
tags: [ICCV, Training Techniques, GPT, Prompting, Evaluation, Language Modeling, Fine
    Tuning, Datasets]
---
Autoregressive (AR) models have achieved unified and strong performance across both visual understanding and image generation tasks. However, removing undesired concepts from AR models while maintaining overall generation quality remains an open challenge. In this paper, we propose Erasure Autoregressive Model (EAR), a fine-tuning method for effective and utility-preserving concept erasure in AR models. Specifically, we introduce Windowed Gradient Accumulation (WGA) strategy to align patch-level decoding with erasure objectives, and Thresholded Loss Masking (TLM) strategy to protect content unrelated to the target concept during fine-tuning. Furthermore, we propose a novel benchmark, Erase Concept Generator and Visual Filter (ECGVF), aim at provide a more rigorous and comprehensive foundation for evaluating concept erasure in AR models. Specifically, we first employ structured templates across diverse large language models (LLMs) to pre-generate a large-scale corpus of target-replacement concept prompt pairs. Subsequently, we generate images from these prompts and subject them to rigorous filtering via a visual classifier to ensure concept fidelity and alignment. Extensive experimental results conducted on the ECGVF benchmark with the AR model Janus-Pro demonstrate that EAR achieves marked improvements in both erasure effectiveness and model utility preservation. Code is available at: https://github.com/immc-lab/ear/