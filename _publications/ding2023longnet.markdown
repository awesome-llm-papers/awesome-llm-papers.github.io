---
layout: publication
title: 'Longnet: Scaling Transformers To 1,000,000,000 Tokens'
authors: Jiayu Ding, Shuming Ma, Li Dong, Xingxing Zhang, Shaohan Huang, Wenhui Wang,
  Furu Wei
conference: No Venue
year: 2023
bibkey: ding2023longnet
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2307.02486'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Ding et al.
---
Scaling sequence length has become a critical demand in the era of large language models. However, existing methods struggle with either computational complexity or model expressivity, rendering the maximum sequence length restricted. In this work, we introduce LongNet, a Transformer variant that can scale sequence length to more than 1 billion tokens, without sacrificing the performance on shorter sequences. Specifically, we propose dilated attention, which expands the attentive field exponentially as the distance grows. LongNet has significant advantages: 1) it has a linear computation complexity and a logarithm dependency between tokens; 2) it can be served as a distributed trainer for extremely long sequences; 3) its dilated attention is a drop-in replacement for standard attention, which can be seamlessly integrated with the existing Transformer-based optimization. Experiments results demonstrate that LongNet yields strong performance on both long-sequence modeling and general language tasks. Our work opens up new possibilities for modeling very long sequences, e.g., treating a whole corpus or even the entire Internet as a sequence.

https://huggingface.co/discussions/paper/64a6234ca3227ff52076ea35