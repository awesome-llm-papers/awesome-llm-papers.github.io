---
layout: publication
title: 'Don''t Look Only Once: Towards Multimodal Interactive Reasoning With Selective
  Visual Revisitation'
authors: Jiwan Chung, Junhyeok Kim, Siyeol Kim, Jaeyoung Lee, Min Soo Kim, Youngjae
  Yu
conference: No Venue
year: 2025
bibkey: chung2025don
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6839543f6451d371f9e83544'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.18842'}]
tags: ["Datasets"]
short_authors: Chung et al.
---
We present v1, a lightweight extension to Multimodal Large Language Models (MLLMs) that enables selective visual revisitation during inference. While current MLLMs typically consume visual input only once and reason purely over internal memory, v1 introduces a simple point-and-copy mechanism that allows the model to dynamically retrieve relevant image regions throughout the reasoning process. This mechanism augments existing architectures with minimal modifications, enabling contextual access to visual tokens based on the model's evolving hypotheses. To train this capability, we construct v1g, a dataset of 300K multimodal reasoning traces with interleaved visual grounding annotations. Experiments on three multimodal mathematical reasoning benchmarks -- MathVista, MathVision, and MathVerse -- demonstrate that v1 consistently improves performance over comparable baselines, particularly on tasks requiring fine-grained visual reference and multi-step reasoning. Our results suggest that dynamic visual access is a promising direction for enhancing grounded multimodal reasoning. Code, models, and data will be released to support future research.

https://huggingface.co/discussions/paper/6839543f6451d371f9e83544