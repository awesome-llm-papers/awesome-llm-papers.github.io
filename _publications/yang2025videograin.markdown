---
layout: publication
title: 'Videograin: Modulating Space-time Attention For Multi-grained Video Editing'
authors: Xiangpeng Yang, Linchao Zhu, Hehe Fan, Yi Yang
conference: No Venue
year: 2025
bibkey: yang2025videograin
additional_links: [{name: Code, url: 'https://knightyxp.github.io/VideoGrain_project_page/'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67bd51620417e7f92283d4e9'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.17258'}]
tags: ["Model Architecture"]
short_authors: Yang et al.
---
Recent advancements in diffusion models have significantly improved video generation and editing capabilities. However, multi-grained video editing, which encompasses class-level, instance-level, and part-level modifications, remains a formidable challenge. The major difficulties in multi-grained editing include semantic misalignment of text-to-region control and feature coupling within the diffusion model. To address these difficulties, we present VideoGrain, a zero-shot approach that modulates space-time (cross- and self-) attention mechanisms to achieve fine-grained control over video content. We enhance text-to-region control by amplifying each local prompt's attention to its corresponding spatial-disentangled region while minimizing interactions with irrelevant areas in cross-attention. Additionally, we improve feature separation by increasing intra-region awareness and reducing inter-region interference in self-attention. Extensive experiments demonstrate our method achieves state-of-the-art performance in real-world scenarios. Our code, data, and demos are available at https://knightyxp.github.io/VideoGrain_project_page/

https://huggingface.co/discussions/paper/67bd51620417e7f92283d4e9