---
layout: publication
title: 'Omnihuman-1: Rethinking The Scaling-up Of One-stage Conditioned Human Animation
  Models'
authors: Gaojie Lin, Jianwen Jiang, Jiaqi Yang, Zerong Zheng, Chao Liang
conference: No Venue
year: 2025
bibkey: lin2025omnihuman
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.01061'}]
tags: ["Applications", "Model Architecture"]
short_authors: Lin et al.
---
End-to-end human animation, such as audio-driven talking human generation, has undergone notable advancements in the recent few years. However, existing methods still struggle to scale up as large general video generation models, limiting their potential in real applications. In this paper, we propose OmniHuman, a Diffusion Transformer-based framework that scales up data by mixing motion-related conditions into the training phase. To this end, we introduce two training principles for these mixed conditions, along with the corresponding model architecture and inference strategy. These designs enable OmniHuman to fully leverage data-driven motion generation, ultimately achieving highly realistic human video generation. More importantly, OmniHuman supports various portrait contents (face close-up, portrait, half-body, full-body), supports both talking and singing, handles human-object interactions and challenging body poses, and accommodates different image styles. Compared to existing end-to-end audio-driven methods, OmniHuman not only produces more realistic videos, but also offers greater flexibility in inputs. It also supports multiple driving modalities (audio-driven, video-driven and combined driving signals). Video samples are provided on the ttfamily project page (https://omnihuman-lab.github.io)

https://huggingface.co/discussions/paper/67a1a7a466a8a88726963f90