---
layout: publication
title: 'Reconstruction Vs. Generation: Taming Optimization Dilemma In Latent Diffusion
  Models'
authors: Jingfeng Yao, Xinggang Wang
conference: No Venue
year: 2025
bibkey: yao2025reconstruction
additional_links: [{name: Code, url: 'https://github.com/hustvl/LightningDiT'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/677753a38376dfe003a3fc2b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.01423'}]
tags: ["Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Jingfeng Yao, Xinggang Wang
---
Latent diffusion models with Transformer architectures excel at generating high-fidelity images. However, recent studies reveal an optimization dilemma in this two-stage design: while increasing the per-token feature dimension in visual tokenizers improves reconstruction quality, it requires substantially larger diffusion models and more training iterations to achieve comparable generation performance. Consequently, existing systems often settle for sub-optimal solutions, either producing visual artifacts due to information loss within tokenizers or failing to converge fully due to expensive computation costs. We argue that this dilemma stems from the inherent difficulty in learning unconstrained high-dimensional latent spaces. To address this, we propose aligning the latent space with pre-trained vision foundation models when training the visual tokenizers. Our proposed VA-VAE (Vision foundation model Aligned Variational AutoEncoder) significantly expands the reconstruction-generation frontier of latent diffusion models, enabling faster convergence of Diffusion Transformers (DiT) in high-dimensional latent spaces. To exploit the full potential of VA-VAE, we build an enhanced DiT baseline with improved training strategies and architecture designs, termed LightningDiT. The integrated system achieves state-of-the-art (SOTA) performance on ImageNet 256x256 generation with an FID score of 1.35 while demonstrating remarkable training efficiency by reaching an FID score of 2.11 in just 64 epochs--representing an over 21 times convergence speedup compared to the original DiT. Models and codes are available at: https://github.com/hustvl/LightningDiT.

https://huggingface.co/discussions/paper/677753a38376dfe003a3fc2b