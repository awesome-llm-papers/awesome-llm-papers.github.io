---
layout: publication
title: 'SRMT: Shared Memory For Multi-agent Lifelong Pathfinding'
authors: Alsu Sagirova, Yuri Kuratov, Mikhail Burtsev
conference: No Venue
year: 2025
bibkey: sagirova2025srmt
additional_links: [{name: Code, url: 'https://github.com/Aloriosa/srmt'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67933d6ab843fda452c68a38'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2501.13200'}]
tags: ["Agentic", "Reinforcement Learning"]
short_authors: Alsu Sagirova, Yuri Kuratov, Mikhail Burtsev
---
Multi-agent reinforcement learning (MARL) demonstrates significant progress in solving cooperative and competitive multi-agent problems in various environments. One of the principal challenges in MARL is the need for explicit prediction of the agents' behavior to achieve cooperation. To resolve this issue, we propose the Shared Recurrent Memory Transformer (SRMT) which extends memory transformers to multi-agent settings by pooling and globally broadcasting individual working memories, enabling agents to exchange information implicitly and coordinate their actions. We evaluate SRMT on the Partially Observable Multi-Agent Pathfinding problem in a toy Bottleneck navigation task that requires agents to pass through a narrow corridor and on a POGEMA benchmark set of tasks. In the Bottleneck task, SRMT consistently outperforms a variety of reinforcement learning baselines, especially under sparse rewards, and generalizes effectively to longer corridors than those seen during training. On POGEMA maps, including Mazes, Random, and MovingAI, SRMT is competitive with recent MARL, hybrid, and planning-based algorithms. These results suggest that incorporating shared recurrent memory into the transformer-based architectures can enhance coordination in decentralized multi-agent systems. The source code for training and evaluation is available on GitHub: https://github.com/Aloriosa/srmt.

https://huggingface.co/discussions/paper/67933d6ab843fda452c68a38