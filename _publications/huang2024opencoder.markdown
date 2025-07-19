---
layout: publication
title: 'Opencoder: The Open Cookbook For Top-tier Code Large Language Models'
authors: Huang et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: huang2024opencoder
citations: 151
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.04905'}]
tags: [Training Techniques, EMNLP, Agentic, Reinforcement Learning, Fine Tuning, Datasets,
  LLM For Code]
---
Large language models (LLMs) for code have become indispensable in various
domains, including code generation, reasoning tasks and agent systems. While
open-access code LLMs are increasingly approaching the performance levels of
proprietary models, high-quality code LLMs suitable for rigorous scientific
investigation, particularly those with reproducible data processing pipelines
and transparent training protocols, remain limited. The scarcity is due to
various challenges, including resource constraints, ethical considerations, and
the competitive advantages of keeping models advanced. To address the gap, we
introduce OpenCoder, a top-tier code LLM that not only achieves performance
comparable to leading models but also serves as an "open cookbook" for the
research community. Unlike most prior efforts, we release not only model
weights and inference code, but also the reproducible training data, complete
data processing pipeline, rigorous experimental ablation results, and detailed
training protocols for open scientific research. Through this comprehensive
release, we identify the key ingredients for building a top-tier code LLM: (1)
code optimized heuristic rules for data cleaning and methods for data
deduplication, (2) recall of text corpus related to code and (3) high-quality
synthetic data in both annealing and supervised fine-tuning stages. By offering
this level of openness, we aim to broaden access to all aspects of a top-tier
code LLM, with OpenCoder serving as both a powerful model and an open
foundation to accelerate research, and enable reproducible advancements in code
AI.