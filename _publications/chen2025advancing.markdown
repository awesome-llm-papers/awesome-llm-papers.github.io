---
layout: publication
title: 'Advancing Multimodal Reasoning: From Optimized Cold Start To Staged Reinforcement
  Learning'
authors: Shuang Chen, Yue Guo, Zhaochen Su, Yafu Li, Yulun Wu, Jiacheng Chen, Jiayu
  Chen, Weijie Wang, Xiaoye Qu, Yu Cheng
conference: No Venue
year: 2025
bibkey: chen2025advancing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.04207'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Chen et al.
---
Inspired by the remarkable reasoning capabilities of Deepseek-R1 in complex textual tasks, many works attempt to incentivize similar capabilities in Multimodal Large Language Models (MLLMs) by directly applying reinforcement learning (RL). However, they still struggle to activate complex reasoning. In this paper, rather than examining multimodal RL in isolation, we delve into current training pipelines and identify three crucial phenomena: 1) Effective cold start initialization is critical for enhancing MLLM reasoning. Intriguingly, we find that initializing with carefully selected text data alone can lead to performance surpassing many recent multimodal reasoning models, even before multimodal RL. 2) Standard GRPO applied to multimodal RL suffers from gradient stagnation, which degrades training stability and performance. 3) Subsequent text-only RL training, following the multimodal RL phase, further enhances multimodal reasoning. This staged training approach effectively balances perceptual grounding and cognitive reasoning development. By incorporating the above insights and addressing multimodal RL issues, we introduce ReVisual-R1, achieving a new state-of-the-art among open-source 7B MLLMs on challenging benchmarks including MathVerse, MathVision, WeMath, LogicVista, DynaMath, and challenging AIME2024 and AIME2025.

https://huggingface.co/discussions/paper/684117e32db29aa7b403afc2