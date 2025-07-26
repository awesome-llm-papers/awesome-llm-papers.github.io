---
layout: publication
title: 'Open-reasoner-zero: An Open Source Approach To Scaling Up Reinforcement Learning
  On The Base Model'
authors: Jingcheng Hu, Yinmin Zhang, Qi Han, Daxin Jiang, Xiangyu Zhang, Heung-yeung
  Shum
conference: No Venue
year: 2025
bibkey: hu2025open
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67eb762481e530baa56dc872'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.24290'}]
tags: ["Efficiency", "Reinforcement Learning"]
short_authors: Hu et al.
---
We introduce Open-Reasoner-Zero, the first open source implementation of large-scale reasoning-oriented RL training focusing on scalability, simplicity and accessibility. Through extensive experiments, we demonstrate that a minimalist approach, vanilla PPO with GAE (lambda=1, gamma=1) and straightforward rule-based rewards, without any KL regularization, is sufficient to scale up both response length and benchmark performance, similar to the phenomenon observed in DeepSeek-R1-Zero. Using the same base model as DeepSeek-R1-Zero-Qwen-32B, our implementation achieves superior performance on AIME2024, MATH500, and the GPQA Diamond benchmark while demonstrating remarkable efficiency -- requiring only a tenth of the training steps, compared to DeepSeek-R1-Zero pipeline. In the spirit of open source, we release our source code, parameter settings, training data, and model weights across various sizes.

https://huggingface.co/discussions/paper/67eb762481e530baa56dc872