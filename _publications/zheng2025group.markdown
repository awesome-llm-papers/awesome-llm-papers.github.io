---
layout: publication
title: Group Sequence Policy Optimization
authors: Chujie Zheng, Shixuan Liu, Mingze Li, Xiong-hui Chen, Bowen Yu, Chang Gao,
  Kai Dang, Yuqiong Liu, Rui Men, An Yang, Jingren Zhou, Junyang Lin
conference: No Venue
year: 2025
bibkey: zheng2025group
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.18071'}]
tags: ["Reinforcement Learning"]
short_authors: Zheng et al.
---
This paper introduces Group Sequence Policy Optimization (GSPO), our stable, efficient, and performant reinforcement learning algorithm for training large language models. Unlike previous algorithms that adopt token-level importance ratios, GSPO defines the importance ratio based on sequence likelihood and performs sequence-level clipping, rewarding, and optimization. We demonstrate that GSPO achieves superior training efficiency and performance compared to the GRPO algorithm, notably stabilizes Mixture-of-Experts (MoE) RL training, and has the potential for simplifying the design of RL infrastructure. These merits of GSPO have contributed to the remarkable improvements in the latest Qwen3 models.

https://huggingface.co/discussions/paper/68831fe7846d2e78b7548ad4