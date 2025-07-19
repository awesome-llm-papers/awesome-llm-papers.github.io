---
layout: publication
title: Process Reinforcement Through Implicit Rewards
authors: Cui et al.
conference: Journal of Artificial Intelligence Research
year: 2025
bibkey: cui2025process
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.01456'}]
tags: [RAG, Training Techniques, Alt, Agentic, Evaluation, Efficiency And Optimization,
  Reinforcement Learning, Fine Tuning, Datasets]
---
Dense process rewards have proven a more effective alternative to the sparse
outcome-level rewards in the inference-time scaling of large language models
(LLMs), particularly in tasks requiring complex multi-step reasoning. While
dense rewards also offer an appealing choice for the reinforcement learning
(RL) of LLMs since their fine-grained rewards have the potential to address
some inherent issues of outcome rewards, such as training efficiency and credit
assignment, this potential remains largely unrealized. This can be primarily
attributed to the challenges of training process reward models (PRMs) online,
where collecting high-quality process labels is prohibitively expensive, making
them particularly vulnerable to reward hacking. To address these challenges, we
propose PRIME (Process Reinforcement through IMplicit rEwards), which enables
online PRM updates using only policy rollouts and outcome labels through
implict process rewards. PRIME combines well with various advantage functions
and forgoes the dedicated reward model training phrase that existing approaches
require, substantially reducing the development overhead. We demonstrate
PRIME's effectiveness on competitional math and coding. Starting from
Qwen2.5-Math-7B-Base, PRIME achieves a 15.1% average improvement across several
key reasoning benchmarks over the SFT model. Notably, our resulting model,
Eurus-2-7B-PRIME, surpasses Qwen2.5-Math-7B-Instruct on seven reasoning
benchmarks with 10% of its training data.