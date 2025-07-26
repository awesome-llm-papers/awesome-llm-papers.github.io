---
layout: publication
title: 'Radial Attention: O(nlog N) Sparse Attention With Energy Decay For Long Video
  Generation'
authors: Xingyang Li, Muyang Li, Tianle Cai, Haocheng Xi, Shuo Yang, Yujun Lin, Lvmin
  Zhang, Songlin Yang, Jinbo Hu, Kelly Peng, Maneesh Agrawala, Ion Stoica, Kurt Keutzer,
  Song Han
conference: No Venue
year: 2025
bibkey: li2025radial
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.19852'}]
tags: ["Model Architecture"]
short_authors: Li et al.
---
Recent advances in diffusion models have enabled high-quality video generation, but the additional temporal dimension significantly increases computational costs, making training and inference on long videos prohibitively expensive. In this paper, we identify a phenomenon we term Spatiotemporal Energy Decay in video diffusion models: post-softmax attention scores diminish as spatial and temporal distance between tokens increase, akin to the physical decay of signal or waves over space and time in nature. Motivated by this, we propose Radial Attention, a scalable sparse attention mechanism with O(n log n) complexity that translates energy decay into exponentially decaying compute density, which is significantly more efficient than standard O(n^2) dense attention and more expressive than linear attention. Specifically, Radial Attention employs a simple, static attention mask where each token attends to spatially nearby tokens, with the attention window size shrinking with temporal distance. Moreover, it allows pre-trained video diffusion models to extend their generation length with efficient LoRA-based fine-tuning. Extensive experiments show that Radial Attention maintains video quality across Wan2.1-14B, HunyuanVideo, and Mochi 1, achieving up to a 1.9times speedup over the original dense attention. With minimal tuning, it enables video generation up to 4times longer while reducing training costs by up to 4.4times compared to direct fine-tuning and accelerating inference by up to 3.7times compared to dense attention inference.

https://huggingface.co/discussions/paper/685d790d61ef876fd500e933