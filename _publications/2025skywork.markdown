---
layout: publication
title: 'Skywork R1V2: Multimodal Hybrid Reinforcement Learning For Reasoning'
authors: Chris, Yichen Wei, Yi Peng, Xiaokun Wang, Weijie Qiu, Wei Shen, Tianyidan
  Xie, Jiangbo Pei, Jianhao Zhang, Yunzhuo Hao, Xuchen Song, Yang Liu, Yahui Zhou
conference: No Venue
year: 2025
bibkey: 2025skywork
additional_links: [{name: Code, url: 'https://huggingface.co/Skywork/Skywork-R1V2-38B'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6809a4ae81a95c83f0c81cda'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.16656'}]
tags: ["Efficiency", "Reinforcement Learning", "Training Techniques"]
short_authors: Chris et al.
---
We present Skywork R1V2, a next-generation multimodal reasoning model and a major leap forward from its predecessor, Skywork R1V. At its core, R1V2 introduces a hybrid reinforcement learning paradigm that harmonizes reward-model guidance with rule-based strategies, thereby addressing the long-standing challenge of balancing sophisticated reasoning capabilities with broad generalization. To further enhance training efficiency, we propose the Selective Sample Buffer (SSB) mechanism, which effectively counters the ``Vanishing Advantages'' dilemma inherent in Group Relative Policy Optimization (GRPO) by prioritizing high-value samples throughout the optimization process. Notably, we observe that excessive reinforcement signals can induce visual hallucinations--a phenomenon we systematically monitor and mitigate through calibrated reward thresholds throughout the training process. Empirical results affirm the exceptional capability of R1V2, with benchmark-leading performances such as 62.6 on OlympiadBench, 79.0 on AIME2024, 63.6 on LiveCodeBench, and 74.0 on MMMU. These results underscore R1V2's superiority over existing open-source models and demonstrate significant progress in closing the performance gap with premier proprietary systems, including Gemini 2.5 and OpenAI o4-mini. The Skywork R1V2 model weights have been publicly released to promote openness and reproducibility https://huggingface.co/Skywork/Skywork-R1V2-38B.

https://huggingface.co/discussions/paper/6809a4ae81a95c83f0c81cda