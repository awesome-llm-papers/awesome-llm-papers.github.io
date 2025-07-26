---
layout: publication
title: 'Qwenlong-l1: Towards Long-context Large Reasoning Models With Reinforcement
  Learning'
authors: Fanqi Wan, Weizhou Shen, Shengyi Liao, Yingcheng Shi, Chenliang Li, Ziyi
  Yang, Ji Zhang, Fei Huang, Jingren Zhou, Ming Yan
conference: No Venue
year: 2025
bibkey: wan2025qwenlong
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.17667'}]
tags: ["Reinforcement Learning"]
short_authors: Wan et al.
---
Recent large reasoning models (LRMs) have demonstrated strong reasoning capabilities through reinforcement learning (RL). These improvements have primarily been observed within the short-context reasoning tasks. In contrast, extending LRMs to effectively process and reason on long-context inputs via RL remains a critical unsolved challenge. To bridge this gap, we first formalize the paradigm of long-context reasoning RL, and identify key challenges in suboptimal training efficiency and unstable optimization process. To address these issues, we propose QwenLong-L1, a framework that adapts short-context LRMs to long-context scenarios via progressive context scaling. Specifically, we utilize a warm-up supervised fine-tuning (SFT) stage to establish a robust initial policy, followed by a curriculum-guided phased RL technique to stabilize the policy evolution, and enhanced with a difficulty-aware retrospective sampling strategy to incentivize the policy exploration. Experiments on seven long-context document question-answering benchmarks demonstrate that QwenLong-L1-32B outperforms flagship LRMs like OpenAI-o3-mini and Qwen3-235B-A22B, achieving performance on par with Claude-3.7-Sonnet-Thinking, demonstrating leading performance among state-of-the-art LRMs. This work advances the development of practical long-context LRMs capable of robust reasoning across information-intensive environments.

https://huggingface.co/discussions/paper/6833d7c6a3262d6b1e4d35c5