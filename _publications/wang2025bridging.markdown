---
layout: publication
title: Bridging Continuous And Discrete Tokens For Autoregressive Visual Generation
authors: Yuqing Wang, Zhijie Lin, Yao Teng, Yuanzhi Zhu, Shuhuai Ren, Jiashi Feng,
  Xihui Liu
conference: No Venue
year: 2025
bibkey: wang2025bridging
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.16430'}]
tags: ["Efficiency", "Has Code", "Training Techniques"]
short_authors: Wang et al.
---
Autoregressive visual generation models typically rely on tokenizers to compress images into tokens that can be predicted sequentially. A fundamental dilemma exists in token representation: discrete tokens enable straightforward modeling with standard cross-entropy loss, but suffer from information loss and tokenizer training instability; continuous tokens better preserve visual details, but require complex distribution modeling, complicating the generation pipeline. In this paper, we propose TokenBridge, which bridges this gap by maintaining the strong representation capacity of continuous tokens while preserving the modeling simplicity of discrete tokens. To achieve this, we decouple discretization from the tokenizer training process through post-training quantization that directly obtains discrete tokens from continuous representations. Specifically, we introduce a dimension-wise quantization strategy that independently discretizes each feature dimension, paired with a lightweight autoregressive prediction mechanism that efficiently model the resulting large token space. Extensive experiments show that our approach achieves reconstruction and generation quality on par with continuous methods while using standard categorical prediction. This work demonstrates that bridging discrete and continuous paradigms can effectively harness the strengths of both approaches, providing a promising direction for high-quality visual generation with simple autoregressive modeling. Project page: https://yuqingwang1029.github.io/TokenBridge.

https://huggingface.co/discussions/paper/67e0bd85b04d9e836829c55f