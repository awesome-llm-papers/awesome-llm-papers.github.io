---
layout: publication
title: 'Fastmoe: A Fast Mixture-of-expert Training System'
authors: Jiaao He et al.
conference: Arxiv
year: 2021
citations: 35
bibkey: he2021fast
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.13262'}, {name: Code,
    url: 'https://github.com/laekov/fastmoe'}]
tags: [Has Code, Model Architecture, Transformer, Applications, Tools, Reinforcement
    Learning, Training Techniques, Large-Scale Training]
---
Mixture-of-Expert (MoE) presents a strong potential in enlarging the size of
language model to trillions of parameters. However, training trillion-scale MoE
requires algorithm and system co-design for a well-tuned high performance
distributed training system. Unfortunately, the only existing platform that
meets the requirements strongly depends on Google's hardware (TPU) and software
(Mesh Tensorflow) stack, and is not open and available to the public,
especially GPU and PyTorch communities.
  In this paper, we present FastMoE, a distributed MoE training system based on
PyTorch with common accelerators. The system provides a hierarchical interface
for both flexible model design and easy adaption to different applications,
such as Transformer-XL and Megatron-LM. Different from direct implementation of
MoE models using PyTorch, the training speed is highly optimized in FastMoE by
sophisticated high-performance acceleration skills. The system supports placing
different experts on multiple GPUs across multiple nodes, enabling enlarging
the number of experts linearly against the number of GPUs. The source of
FastMoE is available at https://github.com/laekov/fastmoe under Apache-2
license.