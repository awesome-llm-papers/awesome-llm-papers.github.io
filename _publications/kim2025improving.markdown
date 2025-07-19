---
layout: publication
title: Improving Constrained Generation In Language Models Via Self-distilled Twisted
  Sequential Monte Carlo
authors: Kim Sooyeon, Nam Giung, Lee Juho
conference: Automatica
year: 2025
bibkey: kim2025improving
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.02315'}]
tags: [Distillation, ASRU, Efficiency And Optimization, GPT, Reinforcement Learning,
  Language Modeling]
---
Recent work has framed constrained text generation with autoregressive language models as a probabilistic inference problem. Among these, Zhao et al. (2024) introduced a promising approach based on twisted Sequential Monte Carlo, which incorporates learned twist functions and twist-induced proposals to guide the generation process. However, in constrained generation settings where the target distribution concentrates on outputs that are unlikely under the base model, learning becomes challenging due to sparse and uninformative reward signals. We show that iteratively refining the base model through self-distillation alleviates this issue by making the model progressively more aligned with the target, leading to substantial gains in generation quality.