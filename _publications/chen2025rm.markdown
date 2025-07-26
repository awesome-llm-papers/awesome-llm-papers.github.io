---
layout: publication
title: 'RM-R1: Reward Modeling As Reasoning'
authors: Xiusi Chen, Gaotang Li, Ziqi Wang, Bowen Jin, Cheng Qian, Yu Wang, Hongru
  Wang, Yu Zhang, Denghui Zhang, Tong Zhang, Hanghang Tong, Heng Ji
conference: No Venue
year: 2025
bibkey: chen2025rm
additional_links: [{name: Code, url: 'https://github.com/RM-R1-UIUC/RM-R1'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/681988d7d6a5fee26b52ac7e'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.02387'}]
tags: ["Reinforcement Learning"]
short_authors: Chen et al.
---
Reward modeling is essential for aligning large language models (LLMs) with human preferences, especially through reinforcement learning from human feedback (RLHF). To provide accurate reward signals, a reward model (RM) should stimulate deep thinking and conduct interpretable reasoning before assigning a score or a judgment. However, existing RMs either produce opaque scalar scores or directly generate the prediction of a preferred answer, making them struggle to integrate natural language critiques, thus lacking interpretability. Inspired by recent advances of long chain-of-thought (CoT) on reasoning-intensive tasks, we hypothesize and validate that integrating reasoning capabilities into reward modeling significantly enhances RM's interpretability and performance. In this work, we introduce a new class of generative reward models -- Reasoning Reward Models (ReasRMs) -- which formulate reward modeling as a reasoning task. We propose a reasoning-oriented training pipeline and train a family of ReasRMs, RM-R1. The training consists of two key stages: (1) distillation of high-quality reasoning chains and (2) reinforcement learning with verifiable rewards. RM-R1 improves LLM rollouts by self-generating reasoning traces or chat-specific rubrics and evaluating candidate responses against them. Empirically, our models achieve state-of-the-art or near state-of-the-art performance of generative RMs across multiple comprehensive reward model benchmarks, outperforming much larger open-weight models (e.g., Llama3.1-405B) and proprietary ones (e.g., GPT-4o) by up to 13.8%. Beyond final performance, we perform thorough empirical analysis to understand the key ingredients of successful ReasRM training. To facilitate future research, we release six ReasRM models along with code and data at https://github.com/RM-R1-UIUC/RM-R1.

https://huggingface.co/discussions/paper/681988d7d6a5fee26b52ac7e