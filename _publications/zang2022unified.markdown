---
layout: publication
title: Unified Vision And Language Prompt Learning
authors: Yuhang Zang, Wei Li, Kaiyang Zhou, Chen Huang, Chen Change Loy
conference: Arxiv
year: 2022
citations: 46
bibkey: zang2022unified
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.07225'}]
tags: [Few-Shot, Reinforcement Learning, Fine-Tuning, Prompting, Multimodal Models]
---
Prompt tuning, a parameter- and data-efficient transfer learning paradigm
that tunes only a small number of parameters in a model's input space, has
become a trend in the vision community since the emergence of large
vision-language models like CLIP. We present a systematic study on two
representative prompt tuning methods, namely text prompt tuning and visual
prompt tuning. A major finding is that none of the unimodal prompt tuning
methods performs consistently well: text prompt tuning fails on data with high
intra-class visual variances while visual prompt tuning cannot handle low
inter-class variances. To combine the best from both worlds, we propose a
simple approach called Unified Prompt Tuning (UPT), which essentially learns a
tiny neural network to jointly optimize prompts across different modalities.
Extensive experiments on over 11 vision datasets show that UPT achieves a
better trade-off than the unimodal counterparts on few-shot learning
benchmarks, as well as on domain generalization benchmarks. Code and models
will be released to facilitate future research.