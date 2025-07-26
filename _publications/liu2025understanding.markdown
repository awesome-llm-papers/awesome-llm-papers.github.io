---
layout: publication
title: 'Understanding R1-zero-like Training: A Critical Perspective'
authors: Zichen Liu, Changyu Chen, Wenjun Li, Penghui Qi, Tianyu Pang, Chao Du, Wee
  Sun Lee, Min Lin
conference: No Venue
year: 2025
bibkey: liu2025understanding
additional_links: [{name: Code, url: 'https://github.com/sail-sg/understand-r1-zero'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67e97f591cb6fc648f642a38'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.20783'}]
tags: ["Training Techniques"]
short_authors: Liu et al.
---
DeepSeek-R1-Zero has shown that reinforcement learning (RL) at scale can directly enhance the reasoning capabilities of LLMs without supervised fine-tuning. In this work, we critically examine R1-Zero-like training by analyzing its two core components: base models and RL. We investigate a wide range of base models, including DeepSeek-V3-Base, to understand how pretraining characteristics influence RL performance. Our analysis reveals that DeepSeek-V3-Base already exhibit ''Aha moment'', while Qwen2.5 base models demonstrate strong reasoning capabilities even without prompt templates, suggesting potential pretraining biases. Additionally, we identify an optimization bias in Group Relative Policy Optimization (GRPO), which artificially increases response length (especially for incorrect outputs) during training. To address this, we introduce Dr. GRPO, an unbiased optimization method that improves token efficiency while maintaining reasoning performance. Leveraging these insights, we present a minimalist R1-Zero recipe that achieves 43.3% accuracy on AIME 2024 with a 7B base model, establishing a new state-of-the-art. Our code is available at https://github.com/sail-sg/understand-r1-zero.

https://huggingface.co/discussions/paper/67e97f591cb6fc648f642a38