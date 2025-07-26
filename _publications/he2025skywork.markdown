---
layout: publication
title: Skywork Open Reasoner 1 Technical Report
authors: Jujie He, Jiacai Liu, Chris Yuhao Liu, Rui Yan, Chaojie Wang, Peng Cheng,
  Xiaoyu Zhang, Fuxiang Zhang, Jiacheng Xu, Wei Shen, Siyuan Li, Liang Zeng, Tianwen
  Wei, Cheng Cheng, Bo An, Yang Liu, Yahui Zhou
conference: No Venue
year: 2025
bibkey: he2025skywork
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6837c344cd1601f5bd6702dd'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.22312'}]
tags: ["Datasets", "Prompting", "Reinforcement Learning", "Training Techniques"]
short_authors: He et al.
---
The success of DeepSeek-R1 underscores the significant role of reinforcement learning (RL) in enhancing the reasoning capabilities of large language models (LLMs). In this work, we present Skywork-OR1, an effective and scalable RL implementation for long Chain-of-Thought (CoT) models. Building on the DeepSeek-R1-Distill model series, our RL approach achieves notable performance gains, increasing average accuracy across AIME24, AIME25, and LiveCodeBench from 57.8% to 72.8% (+15.0%) for the 32B model and from 43.6% to 57.5% (+13.9%) for the 7B model. Our Skywork-OR1-32B model surpasses both DeepSeek-R1 and Qwen3-32B on the AIME24 and AIME25 benchmarks, while achieving comparable results on LiveCodeBench. The Skywork-OR1-7B and Skywork-OR1-Math-7B models demonstrate competitive reasoning capabilities among models of similar size. We perform comprehensive ablation studies on the core components of our training pipeline to validate their effectiveness. Additionally, we thoroughly investigate the phenomenon of entropy collapse, identify key factors affecting entropy dynamics, and demonstrate that mitigating premature entropy collapse is critical for improved test performance. To support community research, we fully open-source our model weights, training code, and training datasets.

https://huggingface.co/discussions/paper/6837c344cd1601f5bd6702dd