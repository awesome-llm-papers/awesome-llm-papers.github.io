---
layout: publication
title: Learnings From Scaling Visual Tokenizers For Reconstruction And Generation
authors: Philippe Hansen-estruch, David Yan, Ching-yao Chung, Orr Zohar, Jialiang
  Wang, Tingbo Hou, Tao Xu, Sriram Vishwanath, Peter Vajda, Xinlei Chen
conference: No Venue
year: 2025
bibkey: hansenestruch2025learnings
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6789e27a810f471d6aa3d4e2'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.09755'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Hansen-estruch et al.
---
Visual tokenization via auto-encoding empowers state-of-the-art image and video generative models by compressing pixels into a latent space. Although scaling Transformer-based generators has been central to recent advances, the tokenizer component itself is rarely scaled, leaving open questions about how auto-encoder design choices influence both its objective of reconstruction and downstream generative performance. Our work aims to conduct an exploration of scaling in auto-encoders to fill in this blank. To facilitate this exploration, we replace the typical convolutional backbone with an enhanced Vision Transformer architecture for Tokenization (ViTok). We train ViTok on large-scale image and video datasets far exceeding ImageNet-1K, removing data constraints on tokenizer scaling. We first study how scaling the auto-encoder bottleneck affects both reconstruction and generation -- and find that while it is highly correlated with reconstruction, its relationship with generation is more complex. We next explored the effect of separately scaling the auto-encoders' encoder and decoder on reconstruction and generation performance. Crucially, we find that scaling the encoder yields minimal gains for either reconstruction or generation, while scaling the decoder boosts reconstruction but the benefits for generation are mixed. Building on our exploration, we design ViTok as a lightweight auto-encoder that achieves competitive performance with state-of-the-art auto-encoders on ImageNet-1K and COCO reconstruction tasks (256p and 512p) while outperforming existing auto-encoders on 16-frame 128p video reconstruction for UCF-101, all with 2-5x fewer FLOPs. When integrated with Diffusion Transformers, ViTok demonstrates competitive performance on image generation for ImageNet-1K and sets new state-of-the-art benchmarks for class-conditional video generation on UCF-101.

https://huggingface.co/discussions/paper/6789e27a810f471d6aa3d4e2