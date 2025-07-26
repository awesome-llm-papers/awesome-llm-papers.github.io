---
layout: publication
title: 'Mergevq: A Unified Framework For Visual Generation And Representation With
  Disentangled Token Merging And Quantization'
authors: Siyuan Li, Luyuan Zhang, Zedong Wang, Juanxi Tian, Cheng Tan, Zicheng Liu,
  Chang Yu, Qingsong Xie, Haonan Lu, Haoqian Wang, Zhen Lei
conference: No Venue
year: 2025
bibkey: li2025mergevq
additional_links: [{name: Code, url: 'https://apexgen-x.github.io/MergeVQ'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67ecc3993d267d266649e10c'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2504.00999'}]
tags: ["Efficiency", "Has Code", "Memory & Context", "Model Architecture", "Tools", "Training Techniques"]
short_authors: Li et al.
---
Masked Image Modeling (MIM) with Vector Quantization (VQ) has achieved great success in both self-supervised pre-training and image generation. However, most existing methods struggle to address the trade-off in shared latent space for generation quality vs. representation learning and efficiency. To push the limits of this paradigm, we propose MergeVQ, which incorporates token merging techniques into VQ-based generative models to bridge the gap between image generation and visual representation learning in a unified architecture. During pre-training, MergeVQ decouples top-k semantics from latent space with the token merge module after self-attention blocks in the encoder for subsequent Look-up Free Quantization (LFQ) and global alignment and recovers their fine-grained details through cross-attention in the decoder for reconstruction. As for the second-stage generation, we introduce MergeAR, which performs KV Cache compression for efficient raster-order prediction. Extensive experiments on ImageNet verify that MergeVQ as an AR generative model achieves competitive performance in both visual representation learning and image generation tasks while maintaining favorable token efficiency and inference speed. The code and model will be available at https://apexgen-x.github.io/MergeVQ.

https://huggingface.co/discussions/paper/67ecc3993d267d266649e10c