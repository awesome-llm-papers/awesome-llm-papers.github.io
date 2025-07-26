---
layout: publication
title: 'Osworld: Benchmarking Multimodal Agents For Open-ended Tasks In Real Computer
  Environments'
authors: Tianbao Xie, Danyang Zhang, Jixuan Chen, Xiaochuan Li, Siheng Zhao, Ruisheng
  Cao, Toh Jing Hua, Zhoujun Cheng, Dongchan Shin, Fangyu Lei, Yitao Liu, Yiheng Xu,
  Shuyan Zhou, Silvio Savarese, Caiming Xiong, Victor Zhong, Tao Yu
conference: No Venue
year: 2024
bibkey: xie2024osworld
additional_links: [{name: Code, url: 'https://os-world.github.io'}, {name: Code, url: 'https://huggingface.co/discussions/paper/66188c70e1abd2f76dab97bb'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.07972'}]
tags: ["Agentic", "Applications", "Evaluation", "Has Code"]
short_authors: Xie et al.
---
Autonomous agents that accomplish complex computer tasks with minimal human interventions have the potential to transform human-computer interaction, significantly enhancing accessibility and productivity. However, existing benchmarks either lack an interactive environment or are limited to environments specific to certain applications or domains, failing to reflect the diverse and complex nature of real-world computer use, thereby limiting the scope of tasks and agent scalability. To address this issue, we introduce OSWorld, the first-of-its-kind scalable, real computer environment for multimodal agents, supporting task setup, execution-based evaluation, and interactive learning across various operating systems such as Ubuntu, Windows, and macOS. OSWorld can serve as a unified, integrated computer environment for assessing open-ended computer tasks that involve arbitrary applications. Building upon OSWorld, we create a benchmark of 369 computer tasks involving real web and desktop apps in open domains, OS file I/O, and workflows spanning multiple applications. Each task example is derived from real-world computer use cases and includes a detailed initial state setup configuration and a custom execution-based evaluation script for reliable, reproducible evaluation. Extensive evaluation of state-of-the-art LLM/VLM-based agents on OSWorld reveals significant deficiencies in their ability to serve as computer assistants. While humans can accomplish over 72.36% of the tasks, the best model achieves only 12.24% success, primarily struggling with GUI grounding and operational knowledge. Comprehensive analysis using OSWorld provides valuable insights for developing multimodal generalist agents that were not possible with previous benchmarks. Our code, environment, baseline models, and data are publicly available at https://os-world.github.io.

https://huggingface.co/discussions/paper/66188c70e1abd2f76dab97bb