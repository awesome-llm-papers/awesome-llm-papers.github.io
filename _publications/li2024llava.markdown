---
layout: publication
title: 'Llava-next-interleave: Tackling Multi-image, Video, And 3D In Large Multimodal
  Models'
authors: Feng Li, Renrui Zhang, Hao Zhang, Yuanhan Zhang, Bo Li, Wei Li, Zejun Ma,
  Chunyuan Li
conference: No Venue
year: 2024
bibkey: li2024llava
additional_links: [{name: Code, url: 'https://github.com/LLaVA-VL/LLaVA-NeXT'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/668f4cdac0af06ce53c13adc'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.07895'}]
tags: ["Applications"]
short_authors: Li et al.
---
Visual instruction tuning has made considerable strides in enhancing the capabilities of Large Multimodal Models (LMMs). However, existing open LMMs largely focus on single-image tasks, their applications to multi-image scenarios remains less explored. Additionally, prior LMM research separately tackles different scenarios, leaving it impossible to generalize cross scenarios with new emerging capabilities. To this end, we introduce LLaVA-NeXT-Interleave, which simultaneously tackles Multi-image, Multi-frame (video), Multi-view (3D), and Multi-patch (single-image) scenarios in LMMs. To enable these capabilities, we regard the interleaved data format as a general template and compile the M4-Instruct dataset with 1,177.6k samples, spanning 4 primary domains with 14 tasks and 41 datasets. We also curate the LLaVA-Interleave Bench to comprehensively evaluate the multi-image performance of LMMs. Through extensive experiments, LLaVA-NeXT-Interleave achieves leading results in multi-image, video, and 3D benchmarks, while maintaining the performance of single-image tasks. Besides, our model also exhibits several emerging capabilities, e.g., transferring tasks across different settings and modalities. Code is available at https://github.com/LLaVA-VL/LLaVA-NeXT

https://huggingface.co/discussions/paper/668f4cdac0af06ce53c13adc