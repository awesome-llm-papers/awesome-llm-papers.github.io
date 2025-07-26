---
layout: publication
title: 'Meissonic: Revitalizing Masked Generative Transformers For Efficient High-resolution
  Text-to-image Synthesis'
authors: Jinbin Bai, Tian Ye, Wei Chow, Enxin Song, Qing-guo Chen, Xiangtai Li, Zhen
  Dong, Lei Zhu, Shuicheng Yan
conference: No Venue
year: 2024
bibkey: bai2024meissonic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.08261'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Bai et al.
---
Diffusion models, such as Stable Diffusion, have made significant strides in visual generation, yet their paradigm remains fundamentally different from autoregressive language models, complicating the development of unified language-vision models. Recent efforts like LlamaGen have attempted autoregressive image generation using discrete VQVAE tokens, but the large number of tokens involved renders this approach inefficient and slow. In this work, we present Meissonic, which elevates non-autoregressive masked image modeling (MIM) text-to-image to a level comparable with state-of-the-art diffusion models like SDXL. By incorporating a comprehensive suite of architectural innovations, advanced positional encoding strategies, and optimized sampling conditions, Meissonic substantially improves MIM's performance and efficiency. Additionally, we leverage high-quality training data, integrate micro-conditions informed by human preference scores, and employ feature compression layers to further enhance image fidelity and resolution. Our model not only matches but often exceeds the performance of existing models like SDXL in generating high-quality, high-resolution images. Extensive experiments validate Meissonic's capabilities, demonstrating its potential as a new standard in text-to-image synthesis. We release a model checkpoint capable of producing 1024 times 1024 resolution images.

https://huggingface.co/discussions/paper/670c85b10b54b420bb46411d