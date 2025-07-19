---
layout: publication
title: 'Pytorch FSDP: Experiences On Scaling Fully Sharded Data Parallel'
authors: Zhao et al.
conference: Proceedings of the VLDB Endowment
year: 2023
bibkey: zhao2023pytorch
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.11277'}]
tags: [RAG, Training Techniques, Efficiency And Optimization, Reinforcement Learning,
  Fine Tuning]
---
It is widely acknowledged that large models have the potential to deliver
superior performance across a broad range of domains. Despite the remarkable
progress made in the field of machine learning systems research, which has
enabled the development and exploration of large models, such abilities remain
confined to a small group of advanced users and industry leaders, resulting in
an implicit technical barrier for the wider community to access and leverage
these technologies. In this paper, we introduce PyTorch Fully Sharded Data
Parallel (FSDP) as an industry-grade solution for large model training. FSDP
has been closely co-designed with several key PyTorch core components including
Tensor implementation, dispatcher system, and CUDA memory caching allocator, to
provide non-intrusive user experiences and high training efficiency.
Additionally, FSDP natively incorporates a range of techniques and settings to
optimize resource utilization across a variety of hardware configurations. The
experimental results demonstrate that FSDP is capable of achieving comparable
performance to Distributed Data Parallel while providing support for
significantly larger models with near-linear scalability in terms of TFLOPS.