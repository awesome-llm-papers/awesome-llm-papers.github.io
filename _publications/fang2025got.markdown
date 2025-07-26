---
layout: publication
title: 'Got: Unleashing Reasoning Capability Of Multimodal Large Language Model For
  Visual Generation And Editing'
authors: Rongyao Fang, Chengqi Duan, Kun Wang, Linjiang Huang, Hao Li, Shilin Yan,
  Hao Tian, Xingyu Zeng, Rui Zhao, Jifeng Dai, Xihui Liu, Hongsheng Li
conference: No Venue
year: 2025
bibkey: fang2025got
additional_links: [{name: Code, url: 'https://github.com/rongyaofang/GoT'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67d3a636db36a4d5d95dbdeb'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2503.10639'}]
tags: ["Datasets", "Has Code", "Prompting", "Tools"]
short_authors: Fang et al.
---
Current image generation and editing methods primarily process textual prompts as direct inputs without reasoning about visual composition and explicit operations. We present Generation Chain-of-Thought (GoT), a novel paradigm that enables generation and editing through an explicit language reasoning process before outputting images. This approach transforms conventional text-to-image generation and editing into a reasoning-guided framework that analyzes semantic relationships and spatial arrangements. We define the formulation of GoT and construct large-scale GoT datasets containing over 9M samples with detailed reasoning chains capturing semantic-spatial relationships. To leverage the advantages of GoT, we implement a unified framework that integrates Qwen2.5-VL for reasoning chain generation with an end-to-end diffusion model enhanced by our novel Semantic-Spatial Guidance Module. Experiments show our GoT framework achieves excellent performance on both generation and editing tasks, with significant improvements over baselines. Additionally, our approach enables interactive visual generation, allowing users to explicitly modify reasoning steps for precise image adjustments. GoT pioneers a new direction for reasoning-driven visual generation and editing, producing images that better align with human intent. To facilitate future research, we make our datasets, code, and pretrained models publicly available at https://github.com/rongyaofang/GoT.

https://huggingface.co/discussions/paper/67d3a636db36a4d5d95dbdeb