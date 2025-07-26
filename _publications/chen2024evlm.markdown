---
layout: publication
title: 'EVLM: An Efficient Vision-language Model For Visual Understanding'
authors: Kaibing Chen, Dong Shen, Hanwen Zhong, Huasong Zhong, Kui Xia, di Xu, Wei
  Yuan, Yifei Hu, Bin Wen, Tianke Zhang, Changyi Liu, Dewen Fan, Huihui Xiao, Jiahong
  Wu, Fan Yang, Size Li, di Zhang
conference: No Venue
year: 2024
bibkey: chen2024evlm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.14177'}]
tags: ["Model Architecture"]
short_authors: Chen et al.
---
In the field of multi-modal language models, the majority of methods are built on an architecture similar to LLaVA. These models use a single-layer ViT feature as a visual prompt, directly feeding it into the language models alongside textual tokens. However, when dealing with long sequences of visual signals or inputs such as videos, the self-attention mechanism of language models can lead to significant computational overhead. Additionally, using single-layer ViT features makes it challenging for large language models to perceive visual signals fully. This paper proposes an efficient multi-modal language model to minimize computational costs while enabling the model to perceive visual signals as comprehensively as possible. Our method primarily includes: (1) employing cross-attention to image-text interaction similar to Flamingo. (2) utilize hierarchical ViT features. (3) introduce the Mixture of Experts (MoE) mechanism to enhance model effectiveness. Our model achieves competitive scores on public multi-modal benchmarks and performs well in tasks such as image captioning and video captioning.

https://huggingface.co/discussions/paper/669dc8569a4bf63e08f5533a