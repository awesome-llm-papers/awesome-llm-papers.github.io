---
layout: publication
title: 'Logic-rl: Unleashing LLM Reasoning With Rule-based Reinforcement Learning'
authors: Tian Xie, Zitian Gao, Qingnan Ren, Haoming Luo, Yuqian Hong, Bryan Dai, Joey
  Zhou, Kai Qiu, Zhirong Wu, Chong Luo
conference: No Venue
year: 2025
bibkey: xie2025logic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.14768'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Xie et al.
---
Inspired by the success of DeepSeek-R1, we explore the potential of rule-based reinforcement learning (RL) in large reasoning models. To analyze reasoning dynamics, we use synthetic logic puzzles as training data due to their controllable complexity and straightforward answer verification. We make some key technical contributions that lead to effective and stable RL training: a system prompt that emphasizes the thinking and answering process, a stringent format reward function that penalizes outputs for taking shortcuts, and a straightforward training recipe that achieves stable convergence. Our 7B model develops advanced reasoning skills-such as reflection, verification, and summarization-that are absent from the logic corpus. Remarkably, after training on just 5K logic problems, it demonstrates generalization abilities to the challenging math benchmarks AIME and AMC.

https://huggingface.co/discussions/paper/67b7f08e357c2729ac20a88f