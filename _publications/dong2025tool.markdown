---
layout: publication
title: 'Tool-star: Empowering Llm-brained Multi-tool Reasoner Via Reinforcement Learning'
authors: Guanting Dong, Yifei Chen, Xiaoxi Li, Jiajie Jin, Hongjin Qian, Yutao Zhu,
  Hangyu Mao, Guorui Zhou, Zhicheng Dou, Ji-rong Wen
conference: No Venue
year: 2025
bibkey: dong2025tool
additional_links: [{name: Code, url: 'https://github.com/dongguanting/Tool-Star'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/682fd6055e83dc3256753187'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.16410'}]
tags: ["Has Code", "Reinforcement Learning", "Tools"]
short_authors: Dong et al.
---
Recently, large language models (LLMs) have shown remarkable reasoning capabilities via large-scale reinforcement learning (RL). However, leveraging the RL algorithm to empower effective multi-tool collaborative reasoning in LLMs remains an open challenge. In this paper, we introduce Tool-Star, an RL-based framework designed to empower LLMs to autonomously invoke multiple external tools during stepwise reasoning. Tool-Star integrates six types of tools and incorporates systematic designs in both data synthesis and training. To address the scarcity of tool-use data, we propose a general tool-integrated reasoning data synthesis pipeline, which combines tool-integrated prompting with hint-based sampling to automatically and scalably generate tool-use trajectories. A subsequent quality normalization and difficulty-aware classification process filters out low-quality samples and organizes the dataset from easy to hard. Furthermore, we propose a two-stage training framework to enhance multi-tool collaborative reasoning by: (1) cold-start fine-tuning, which guides LLMs to explore reasoning patterns via tool-invocation feedback; and (2) a multi-tool self-critic RL algorithm with hierarchical reward design, which reinforces reward understanding and promotes effective tool collaboration. Experimental analyses on over 10 challenging reasoning benchmarks highlight the effectiveness and efficiency of Tool-Star. The code is available at https://github.com/dongguanting/Tool-Star.

https://huggingface.co/discussions/paper/682fd6055e83dc3256753187