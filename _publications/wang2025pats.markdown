---
layout: publication
title: 'PATS: Process-level Adaptive Thinking Mode Switching'
authors: Yi Wang, Junxiao Liu, Shimao Zhang, Jiajun Chen, Shujian Huang
conference: No Venue
year: 2025
bibkey: wang2025pats
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.19250'}]
tags: ["Efficiency", "Reinforcement Learning", "Training Techniques"]
short_authors: Wang et al.
---
Current large-language models (LLMs) typically adopt a fixed reasoning strategy, either simple or complex, for all questions, regardless of their difficulty. This neglect of variation in task and reasoning process complexity leads to an imbalance between performance and efficiency. Existing methods attempt to implement training-free fast-slow thinking system switching to handle problems of varying difficulty, but are limited by coarse-grained solution-level strategy adjustments. To address this issue, we propose a novel reasoning paradigm: Process-Level Adaptive Thinking Mode Switching (PATS), which enables LLMs to dynamically adjust their reasoning strategy based on the difficulty of each step, optimizing the balance between accuracy and computational efficiency. Our approach integrates Process Reward Models (PRMs) with Beam Search, incorporating progressive mode switching and bad-step penalty mechanisms. Experiments on diverse mathematical benchmarks demonstrate that our methodology achieves high accuracy while maintaining moderate token usage. This study emphasizes the significance of process-level, difficulty-aware reasoning strategy adaptation, offering valuable insights into efficient inference for LLMs.

https://huggingface.co/discussions/paper/68355ce16a9c239ada09f9a9