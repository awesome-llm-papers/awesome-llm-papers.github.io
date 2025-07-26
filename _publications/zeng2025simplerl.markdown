---
layout: publication
title: 'Simplerl-zoo: Investigating And Taming Zero Reinforcement Learning For Open
  Base Models In The Wild'
authors: Weihao Zeng, Yuzhen Huang, Qian Liu, Wei Liu, Keqing He, Zejun Ma, Junxian
  He
conference: No Venue
year: 2025
bibkey: zeng2025simplerl
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67e22ce3155ea10f2fdbe6c0'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.18892'}]
tags: ["Reinforcement Learning", "Tools"]
short_authors: Zeng et al.
---
DeepSeek-R1 has shown that long chain-of-thought (CoT) reasoning can naturally emerge through a simple reinforcement learning (RL) framework with rule-based rewards, where the training may directly start from the base models-a paradigm referred to as zero RL training. Most recent efforts to reproduce zero RL training have primarily focused on the Qwen2.5 model series, which may not be representative as we find the base models already exhibit strong instruction-following and self-reflection abilities. In this work, we investigate zero RL training across 10 diverse base models, spanning different families and sizes including LLama3-8B, Mistral-7B/24B, DeepSeek-Math-7B, Qwen2.5-math-7B, and all Qwen2.5 models from 0.5B to 32B. Leveraging several key design strategies-such as adjusting format reward and controlling query difficulty-we achieve substantial improvements in both reasoning accuracy and response length across most settings. However, by carefully monitoring the training dynamics, we observe that different base models exhibit distinct patterns during training. For instance, the increased response length does not always correlate with the emergence of certain cognitive behaviors such as verification (i.e., the "aha moment"). Notably, we observe the "aha moment" for the first time in small models not from the Qwen family. We share the key designs that enable successful zero RL training, along with our findings and practices. To facilitate further research, we open-source the code, models, and analysis tools.

https://huggingface.co/discussions/paper/67e22ce3155ea10f2fdbe6c0