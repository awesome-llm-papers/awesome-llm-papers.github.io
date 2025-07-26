---
layout: publication
title: 'Janus: Decoupling Visual Encoding For Unified Multimodal Understanding And
  Generation'
authors: Chengyue Wu, Xiaokang Chen, Zhiyu Wu, Yiyang Ma, Xingchao Liu, Zizheng Pan,
  Wen Liu, Zhenda Xie, Xingkai Yu, Chong Ruan, Ping Luo
conference: No Venue
year: 2024
bibkey: wu2024janus
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6711d3f4b6b1901abbf8c246'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.13848'}]
tags: ["Model Architecture"]
short_authors: Wu et al.
---
In this paper, we introduce Janus, an autoregressive framework that unifies multimodal understanding and generation. Prior research often relies on a single visual encoder for both tasks, such as Chameleon. However, due to the differing levels of information granularity required by multimodal understanding and generation, this approach can lead to suboptimal performance, particularly in multimodal understanding. To address this issue, we decouple visual encoding into separate pathways, while still leveraging a single, unified transformer architecture for processing. The decoupling not only alleviates the conflict between the visual encoder's roles in understanding and generation, but also enhances the framework's flexibility. For instance, both the multimodal understanding and generation components can independently select their most suitable encoding methods. Experiments show that Janus surpasses previous unified model and matches or exceeds the performance of task-specific models. The simplicity, high flexibility, and effectiveness of Janus make it a strong candidate for next-generation unified multimodal models.

https://huggingface.co/discussions/paper/6711d3f4b6b1901abbf8c246