---
layout: publication
title: 'T2I-R1: Reinforcing Image Generation With Collaborative Semantic-level And
  Token-level Cot'
authors: Dongzhi Jiang, Ziyu Guo, Renrui Zhang, Zhuofan Zong, Hao Li, Le Zhuo, Shilin
  Yan, Pheng-ann Heng, Hongsheng Li
conference: No Venue
year: 2025
bibkey: jiang2025t2i
additional_links: [{name: Code, url: 'https://github.com/CaraJ7/T2I-R1'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/681428dfbcdf962d03da281c'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.00703'}]
tags: ["Reinforcement Learning"]
short_authors: Jiang et al.
---
Recent advancements in large language models have demonstrated how chain-of-thought (CoT) and reinforcement learning (RL) can improve performance. However, applying such reasoning strategies to the visual generation domain remains largely unexplored. In this paper, we present T2I-R1, a novel reasoning-enhanced text-to-image generation model, powered by RL with a bi-level CoT reasoning process. Specifically, we identify two levels of CoT that can be utilized to enhance different stages of generation: (1) the semantic-level CoT for high-level planning of the prompt and (2) the token-level CoT for low-level pixel processing during patch-by-patch generation. To better coordinate these two levels of CoT, we introduce BiCoT-GRPO with an ensemble of generation rewards, which seamlessly optimizes both generation CoTs within the same training step. By applying our reasoning strategies to the baseline model, Janus-Pro, we achieve superior performance with 13% improvement on T2I-CompBench and 19% improvement on the WISE benchmark, even surpassing the state-of-the-art model FLUX.1. Code is available at: https://github.com/CaraJ7/T2I-R1

https://huggingface.co/discussions/paper/681428dfbcdf962d03da281c