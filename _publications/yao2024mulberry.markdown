---
layout: publication
title: 'Mulberry: Empowering MLLM With O1-like Reasoning And Reflection Via Collective
  Monte Carlo Tree Search'
authors: Huanjin Yao, Jiaxing Huang, Wenhao Wu, Jingyi Zhang, Yibo Wang, Shunyu Liu,
  Yingjie Wang, Yuxin Song, Haocheng Feng, Li Shen, Dacheng Tao
conference: No Venue
year: 2024
bibkey: yao2024mulberry
additional_links: [{name: Code, url: 'https://github.com/HJYao00/Mulberry'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/676d843e92c4a8fe495328d3'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2412.18319'}]
tags: ["Datasets", "Fine-Tuning", "Has Code"]
short_authors: Yao et al.
---
In this work, we aim to develop an MLLM that understands and solves questions by learning to create each intermediate step of the reasoning involved till the final answer. To this end, we propose Collective Monte Carlo Tree Search (CoMCTS), a new learning-to-reason method for MLLMs, which introduces the concept of collective learning into ``tree search'' for effective and efficient reasoning-path searching and learning. The core idea of CoMCTS is to leverage collective knowledge from multiple models to collaboratively conjecture, search and identify effective reasoning paths toward correct answers via four iterative operations including Expansion, Simulation and Error Positioning, Backpropagation, and Selection. Using CoMCTS, we construct Mulberry-260k, a multimodal dataset with a tree of rich, explicit and well-defined reasoning nodes for each question. With Mulberry-260k, we perform collective SFT to train our model, Mulberry, a series of MLLMs with o1-like step-by-step Reasoning and Reflection capabilities. Extensive experiments demonstrate the superiority of our proposed methods on various benchmarks. Code will be available at https://github.com/HJYao00/Mulberry

https://huggingface.co/discussions/paper/676d843e92c4a8fe495328d3