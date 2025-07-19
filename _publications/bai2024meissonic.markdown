---
layout: publication
title: 'Meissonic: Revitalizing Masked Generative Transformers For Efficient High-resolution
  Text-to-image Synthesis'
authors: Bai et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: bai2024meissonic
citations: 1370
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.08261'}]
tags: [RAG, Training Techniques, GPT, CVPR, Transformer, Model Architecture, Efficiency
    And Optimization, Merging]
---
We present Meissonic, which elevates non-autoregressive masked image modeling
(MIM) text-to-image to a level comparable with state-of-the-art diffusion
models like SDXL. By incorporating a comprehensive suite of architectural
innovations, advanced positional encoding strategies, and optimized sampling
conditions, Meissonic substantially improves MIM's performance and efficiency.
Additionally, we leverage high-quality training data, integrate
micro-conditions informed by human preference scores, and employ feature
compression layers to further enhance image fidelity and resolution. Our model
not only matches but often exceeds the performance of existing models like SDXL
in generating high-quality, high-resolution images. Extensive experiments
validate Meissonic's capabilities, demonstrating its potential as a new
standard in text-to-image synthesis. We release a model checkpoint capable of
producing \\(1024 \times 1024\\) resolution images.