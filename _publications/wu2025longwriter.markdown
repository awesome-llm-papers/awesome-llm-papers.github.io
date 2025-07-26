---
layout: publication
title: 'Longwriter-zero: Mastering Ultra-long Text Generation Via Reinforcement Learning'
authors: Yuhao Wu, Yushi Bai, Zhiqiang Hu, Roy Ka-wei Lee, Juanzi Li
conference: No Venue
year: 2025
bibkey: wu2025longwriter
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.18841'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Wu et al.
---
Ultra-long generation by large language models (LLMs) is a widely demanded scenario, yet it remains a significant challenge due to their maximum generation length limit and overall quality degradation as sequence length increases. Previous approaches, exemplified by LongWriter, typically rely on ''teaching'', which involves supervised fine-tuning (SFT) on synthetic long-form outputs. However, this strategy heavily depends on synthetic SFT data, which is difficult and costly to construct, often lacks coherence and consistency, and tends to be overly artificial and structurally monotonous. In this work, we propose an incentivization-based approach that, starting entirely from scratch and without relying on any annotated or synthetic data, leverages reinforcement learning (RL) to foster the emergence of ultra-long, high-quality text generation capabilities in LLMs. We perform RL training starting from a base model, similar to R1-Zero, guiding it to engage in reasoning that facilitates planning and refinement during the writing process. To support this, we employ specialized reward models that steer the LLM towards improved length control, writing quality, and structural formatting. Experimental evaluations show that our LongWriter-Zero model, trained from Qwen2.5-32B, consistently outperforms traditional SFT methods on long-form writing tasks, achieving state-of-the-art results across all metrics on WritingBench and Arena-Write, and even surpassing 100B+ models such as DeepSeek R1 and Qwen3-235B. We open-source our data and model checkpoints under https://huggingface.co/THU-KEG/LongWriter-Zero-32B

https://huggingface.co/discussions/paper/685a0f340e4ad7e219758519