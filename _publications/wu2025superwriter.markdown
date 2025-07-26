---
layout: publication
title: 'Superwriter: Reflection-driven Long-form Generation With Large Language Models'
authors: Yuhao Wu, Yushi Bai, Zhiqiang Hu, Juanzi Li, Roy Ka-wei Lee
conference: No Venue
year: 2025
bibkey: wu2025superwriter
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.04180'}]
tags: ["Tools"]
short_authors: Wu et al.
---
Long-form text generation remains a significant challenge for large language models (LLMs), particularly in maintaining coherence, ensuring logical consistency, and preserving text quality as sequence length increases. To address these limitations, we propose SuperWriter-Agent, an agent-based framework designed to enhance the quality and consistency of long-form text generation. SuperWriter-Agent introduces explicit structured thinking-through planning and refinement stages into the generation pipeline, guiding the model to follow a more deliberate and cognitively grounded process akin to that of a professional writer. Based on this framework, we construct a supervised fine-tuning dataset to train a 7B SuperWriter-LM. We further develop a hierarchical Direct Preference Optimization (DPO) procedure that uses Monte Carlo Tree Search (MCTS) to propagate final quality assessments and optimize each generation step accordingly. Empirical results across diverse benchmarks demonstrate that SuperWriter-LM achieves state-of-the-art performance, surpassing even larger-scale baseline models in both automatic evaluation and human evaluation. Furthermore, comprehensive ablation studies demonstrate the effectiveness of hierarchical DPO and underscore the value of incorporating structured thinking steps to improve the quality of long-form text generation.

https://huggingface.co/discussions/paper/6840fefc3098ab525906d89c