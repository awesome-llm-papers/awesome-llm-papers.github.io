---
layout: publication
title: Faster Video Diffusion With Trainable Sparse Attention
authors: Peiyuan Zhang, Haofeng Huang, Yongqi Chen, Will Lin, Zhengzhong Liu, Ion
  Stoica, Eric P. Xing, Hao Zhang
conference: No Venue
year: 2025
bibkey: zhang2025faster
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.13389'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Zhang et al.
---
Scaling video diffusion transformers (DiTs) is limited by their quadratic 3D attention, even though most of the attention mass concentrates on a small subset of positions. We turn this observation into VSA, a trainable, hardware-efficient sparse attention that replaces full attention at both training and inference. In VSA, a lightweight coarse stage pools tokens into tiles and identifies high-weight critical tokens; a fine stage computes token-level attention only inside those tiles subjecting to block computing layout to ensure hard efficiency. This leads to a single differentiable kernel that trains end-to-end, requires no post-hoc profiling, and sustains 85% of FlashAttention3 MFU. We perform a large sweep of ablation studies and scaling-law experiments by pretraining DiTs from 60M to 1.4B parameters. VSA reaches a Pareto point that cuts training FLOPS by 2.53times with no drop in diffusion loss. Retrofitting the open-source Wan-2.1 model speeds up attention time by 6times and lowers end-to-end generation time from 31s to 18s with comparable quality. These results establish trainable sparse attention as a practical alternative to full attention and a key enabler for further scaling of video diffusion models.

https://huggingface.co/discussions/paper/682c27e3fffb36958f8cd8c2