---
layout: publication
title: 'Vitcod: Vision Transformer Acceleration Via Dedicated Algorithm And Accelerator
  Co-design'
authors: You et al.
conference: 2023 IEEE International Symposium on High-Performance Computer Architecture
  (HPCA)
year: 2022
bibkey: you2022vitcod
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.09573'}]
tags: [Attention Mechanism, Tools, Transformer, Model Architecture, Efficiency And
    Optimization]
---
Vision Transformers (ViTs) have achieved state-of-the-art performance on
various vision tasks. However, ViTs' self-attention module is still arguably a
major bottleneck, limiting their achievable hardware efficiency. Meanwhile,
existing accelerators dedicated to NLP Transformers are not optimal for ViTs.
This is because there is a large difference between ViTs and NLP Transformers:
ViTs have a relatively fixed number of input tokens, whose attention maps can
be pruned by up to 90% even with fixed sparse patterns; while NLP Transformers
need to handle input sequences of varying numbers of tokens and rely on
on-the-fly predictions of dynamic sparse attention patterns for each input to
achieve a decent sparsity (e.g., >=50%). To this end, we propose a dedicated
algorithm and accelerator co-design framework dubbed ViTCoD for accelerating
ViTs. Specifically, on the algorithm level, ViTCoD prunes and polarizes the
attention maps to have either denser or sparser fixed patterns for regularizing
two levels of workloads without hurting the accuracy, largely reducing the
attention computations while leaving room for alleviating the remaining
dominant data movements; on top of that, we further integrate a lightweight and
learnable auto-encoder module to enable trading the dominant high-cost data
movements for lower-cost computations. On the hardware level, we develop a
dedicated accelerator to simultaneously coordinate the enforced denser/sparser
workloads and encoder/decoder engines for boosted hardware utilization.
Extensive experiments and ablation studies validate that ViTCoD largely reduces
the dominant data movement costs, achieving speedups of up to 235.3x, 142.9x,
86.0x, 10.1x, and 6.8x over general computing platforms CPUs, EdgeGPUs, GPUs,
and prior-art Transformer accelerators SpAtten and Sanger under an attention
sparsity of 90%, respectively.