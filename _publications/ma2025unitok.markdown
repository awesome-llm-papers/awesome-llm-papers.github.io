---
layout: publication
title: 'Unitok: A Unified Tokenizer For Visual Generation And Understanding'
authors: Chuofan Ma, Yi Jiang, Junfeng Wu, Jihan Yang, Xin Yu, Zehuan Yuan, Bingyue
  Peng, Xiaojuan Qi
conference: No Venue
year: 2025
bibkey: ma2025unitok
additional_links: [{name: Code, url: 'https://github.com/FoundationVision/UniTok'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67c13c6ad8247a49b8090003'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.20321'}]
tags: ["Tools"]
short_authors: Ma et al.
---
The representation disparity between visual generation and understanding imposes a critical gap in integrating these capabilities into a single framework. To bridge this gap, we introduce UniTok, a discrete visual tokenizer that encodes fine-grained details for generation while also capturing high-level semantics for understanding. Despite recent studies have shown that these objectives could induce loss conflicts in training, we reveal that the underlying bottleneck stems from limited representational capacity of discrete tokens. We address this by introducing multi-codebook quantization, which divides vector quantization with several independent sub-codebooks to expand the latent feature space, while avoiding training instability caused by overlarge codebooks. Our method significantly raises the upper limit of unified discrete tokenizers to match or even surpass domain-specific continuous tokenizers. For instance, UniTok achieves a remarkable rFID of 0.38 (versus 0.87 for SD-VAE) and a zero-shot accuracy of 78.6% (versus 76.2% for CLIP) on ImageNet. Our code is available at https://github.com/FoundationVision/UniTok.

https://huggingface.co/discussions/paper/67c13c6ad8247a49b8090003