---
layout: publication
title: Vision Foundation Models As Effective Visual Tokenizers For Autoregressive
  Image Generation
authors: Anlin Zheng, Xin Wen, Xuanyang Zhang, Chuofan Ma, Tiancai Wang, Gang Yu,
  Xiangyu Zhang, Xiaojuan Qi
conference: No Venue
year: 2025
bibkey: zheng2025vision
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6874b80f257d4f04353703b0'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.08441'}]
tags: ["Efficiency"]
short_authors: Zheng et al.
---
Leveraging the powerful representations of pre-trained vision foundation models -- traditionally used for visual comprehension -- we explore a novel direction: building an image tokenizer directly atop such models, a largely underexplored area. Specifically, we employ a frozen vision foundation model as the encoder of our tokenizer. To enhance its effectiveness, we introduce two key components: (1) a region-adaptive quantization framework that reduces redundancy in the pre-trained features on regular 2D grids, and (2) a semantic reconstruction objective that aligns the tokenizer's outputs with the foundation model's representations to preserve semantic fidelity. Based on these designs, our proposed image tokenizer, VFMTok, achieves substantial improvements in image reconstruction and generation quality, while also enhancing token efficiency. It further boosts autoregressive (AR) generation -- achieving a gFID of 2.07 on ImageNet benchmarks, while accelerating model convergence by three times, and enabling high-fidelity class-conditional synthesis without the need for classifier-free guidance (CFG). The code will be released publicly to benefit the community.

https://huggingface.co/discussions/paper/6874b80f257d4f04353703b0