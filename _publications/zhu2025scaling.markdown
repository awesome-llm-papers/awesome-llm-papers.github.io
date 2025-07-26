---
layout: publication
title: Scaling Test-time Compute For LLM Agents
authors: King Zhu, Hanhao Li, Siwei Wu, Tianshun Xing, Dehua Ma, Xiangru Tang, Minghao
  Liu, Jian Yang, Jiaheng Liu, Yuchen Eleanor Jiang, Changwang Zhang, Chenghua Lin,
  Jun Wang, Ge Zhang, Wangchunshu Zhou
conference: No Venue
year: 2025
bibkey: zhu2025scaling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.12928'}]
tags: ["Agentic"]
short_authors: Zhu et al.
---
Scaling test time compute has shown remarkable success in improving the reasoning abilities of large language models (LLMs). In this work, we conduct the first systematic exploration of applying test-time scaling methods to language agents and investigate the extent to which it improves their effectiveness. Specifically, we explore different test-time scaling strategies, including: (1) parallel sampling algorithms; (2) sequential revision strategies; (3) verifiers and merging methods; (4)strategies for diversifying rollouts.We carefully analyze and ablate the impact of different design strategies on applying test-time scaling on language agents, and have follow findings: 1. Scaling test time compute could improve the performance of agents. 2. Knowing when to reflect is important for agents. 3. Among different verification and result merging approaches, the list-wise method performs best. 4. Increasing diversified rollouts exerts a positive effect on the agent's task performance.

https://huggingface.co/discussions/paper/6851dd060164cd13167103e6