---
layout: publication
title: 'Octothinker: Mid-training Incentivizes Reinforcement Learning Scaling'
authors: Zengzhi Wang, Fan Zhou, Xuefeng Li, Pengfei Liu
conference: No Venue
year: 2025
bibkey: wang2025octothinker
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.20512'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Wang et al.
---
Different base language model families, such as Llama and Qwen, exhibit divergent behaviors during post-training with reinforcement learning (RL), especially on reasoning-intensive tasks. What makes a base language model suitable for reinforcement learning? Gaining deeper insight into this question is essential for developing RL-scalable foundation models of the next generation. In this work, we investigate how mid-training strategies shape RL dynamics, focusing on two representative model families: Qwen and Llama. Our study reveals that (1) high-quality mathematical corpora, such as MegaMath-Web-Pro, significantly improve both base model and RL performance, while existing alternatives (e.g., FineMath-4plus) fail to do so; (2) further adding QA-style data, particularly long chain-of-thought (CoT) reasoning examples, enhances RL outcomes, and instruction data further unlocks this effect; (3) while long-CoT improves reasoning depth, it can also induce verbosity of model responses and unstability of RL training, underscoring the importance of data formatting; (4) scaling mid-training consistently leads to stronger downstream RL performance. Building on these insights, we introduce a two-stage mid-training strategy, Stable-then-Decay, in which base models are first trained on 200B tokens with a constant learning rate, followed by 20B tokens across three CoT-focused branches with learning rate decay. This yields OctoThinker, a family of models demonstrating strong RL compatibility and closing the performance gap with more RL-friendly model families, i.e., Qwen. We hope our work will help shape pre-training strategies for foundation models in the RL era. To support further research, we release our open-source models along with a curated math reasoning-intensive corpus of over 70 billion tokens (i.e., MegaMath-Web-Pro-Max).

https://huggingface.co/discussions/paper/685cb8d7696820ba1f28f29a