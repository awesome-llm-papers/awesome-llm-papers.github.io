---
layout: publication
title: 'Mom: Linear Sequence Modeling With Mixture-of-memories'
authors: Jusen Du, Weigao Sun, Disen Lan, Jiaxi Hu, Yu Cheng
conference: No Venue
year: 2025
bibkey: du2025mom
additional_links: [{name: Code, url: 'https://github.com/OpenSparseLLMs/MoM'}, {name: Code,
    url: 'https://github.com/OpenSparseLLMs/Linear-MoE'}, {name: Code, url: 'https://huggingface.co/discussions/paper/67b6dc1ca7567156c65478b8'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.13685'}]
tags: ["Model Architecture"]
short_authors: Du et al.
---
Linear sequence modeling methods, such as linear attention, state space modeling, and linear RNNs, offer significant efficiency improvements by reducing the complexity of training and inference. However, these methods typically compress the entire input sequence into a single fixed-size memory state, which leads to suboptimal performance on recall-intensive downstream tasks. Drawing inspiration from neuroscience, particularly the brain's ability to maintain robust long-term memory while mitigating "memory interference", we introduce a novel architecture called Mixture-of-Memories (MoM). MoM utilizes multiple independent memory states, with a router network directing input tokens to specific memory states. This approach greatly enhances the overall memory capacity while minimizing memory interference. As a result, MoM performs exceptionally well on recall-intensive tasks, surpassing existing linear sequence modeling techniques. Despite incorporating multiple memory states, the computation of each memory state remains linear in complexity, allowing MoM to retain the linear-complexity advantage during training, while constant-complexity during inference. Our experimental results show that MoM significantly outperforms current linear sequence models on downstream language tasks, particularly recall-intensive tasks, and even achieves performance comparable to Transformer models. The code is released at https://github.com/OpenSparseLLMs/MoM and is also released as a part of https://github.com/OpenSparseLLMs/Linear-MoE.

https://huggingface.co/discussions/paper/67b6dc1ca7567156c65478b8