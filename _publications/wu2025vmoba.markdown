---
layout: publication
title: 'Vmoba: Mixture-of-block Attention For Video Diffusion Models'
authors: Jianzong Wu, Liang Hou, Haotian Yang, Xin Tao, Ye Tian, Pengfei Wan, di Zhang,
  Yunhai Tong
conference: No Venue
year: 2025
bibkey: wu2025vmoba
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.23858'}]
tags: ["Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Wu et al.
---
The quadratic complexity of full attention mechanisms poses a significant bottleneck for Video Diffusion Models (VDMs) aiming to generate long-duration, high-resolution videos. While various sparse attention methods have been proposed, many are designed as training-free inference accelerators or do not optimally capture the unique spatio-temporal characteristics inherent in video data when trained natively. This paper introduces Video Mixture of Block Attention (VMoBA), a novel sparse attention mechanism specifically adapted for VDMs. Motivated by an in-depth analysis of attention patterns within pre-trained video transformers, which revealed strong spatio-temporal locality, varying query importance, and head-specific concentration levels, VMoBA enhances the original MoBA framework with three key modifications: (1) a layer-wise recurrent block partition scheme (1D-2D-3D) to dynamically adapt to diverse spatio-temporal attention patterns and improve efficiency; (2) global block selection to prioritize the most salient query-key block interactions across an entire attention head; and (3) threshold-based block selection to dynamically determine the number of attended blocks based on their cumulative similarity. Extensive experiments demonstrate that VMoBA significantly accelerates the training of VDMs on longer sequences, achieving 2.92x FLOPs and 1.48x latency speedup, while attaining comparable or even superior generation quality to full attention. Furthermore, VMoBA exhibits competitive performance in training-free inference, offering 2.40x FLOPs and 1.35x latency speedup for high-res video generation.

https://huggingface.co/discussions/paper/686347d3588cea0da970c890