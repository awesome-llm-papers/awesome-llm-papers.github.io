---
layout: publication
title: Fast Video Generation With Sliding Tile Attention
authors: Peiyuan Zhang, Yongqi Chen, Runlong Su, Hangliang Ding, Ion Stoica, Zhenghong
  Liu, Hao Zhang
conference: No Venue
year: 2025
bibkey: zhang2025fast
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.04507'}]
tags: ["Memory & Context", "Training Techniques"]
short_authors: Zhang et al.
---
Diffusion Transformers (DiTs) with 3D full attention power state-of-the-art video generation, but suffer from prohibitive compute cost -- when generating just a 5-second 720P video, attention alone takes 800 out of 945 seconds of total inference time. This paper introduces sliding tile attention (STA) to address this challenge. STA leverages the observation that attention scores in pretrained video diffusion models predominantly concentrate within localized 3D windows. By sliding and attending over the local spatial-temporal region, STA eliminates redundancy from full attention. Unlike traditional token-wise sliding window attention (SWA), STA operates tile-by-tile with a novel hardware-aware sliding window design, preserving expressiveness while being hardware-efficient. With careful kernel-level optimizations, STA offers the first efficient 2D/3D sliding-window-like attention implementation, achieving 58.79% MFU. Precisely, STA accelerates attention by 2.8-17x over FlashAttention-2 (FA2) and 1.6-10x over FlashAttention-3 (FA3). On the leading video DiT, HunyuanVideo, STA reduces end-to-end latency from 945s (FA3) to 685s without quality degradation, requiring no training. Enabling finetuning further lowers latency to 268s with only a 0.09% drop on VBench.

https://huggingface.co/discussions/paper/67a98cd7b8b21202c90047c5