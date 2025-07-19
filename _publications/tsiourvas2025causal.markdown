---
layout: publication
title: 'Causal LLM Routing: End-to-end Regret Minimization From Observational Data'
authors: Tsiourvas Asterios, Sun Wei, Perakis Georgia
conference: Journal of the Royal Statistical Society. Series A (General)
year: 2025
bibkey: tsiourvas2025causal
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.16037'}]
tags: [Tools, Evaluation, Model Architecture, Efficiency And Optimization, Datasets]
---
LLM routing aims to select the most appropriate model for each query, balancing competing performance metrics such as accuracy and cost across a pool of language models. Prior approaches typically adopt a decoupled strategy, where the metrics are first predicted and the model is then selected based on these estimates. This setup is prone to compounding errors and often relies on full-feedback data, where each query is evaluated by all candidate models, which is costly to obtain and maintain in practice. In contrast, we learn from observational data, which records only the outcome of the model actually deployed. We propose a causal end-to-end framework that learns routing policies by minimizing decision-making regret from observational data. To enable efficient optimization, we introduce two theoretically grounded surrogate objectives: a classification-based upper bound, and a softmax-weighted regret approximation shown to recover the optimal policy at convergence. We further extend our framework to handle heterogeneous cost preferences via an interval-conditioned architecture. Experiments on public benchmarks show that our method outperforms existing baselines, achieving state-of-the-art performance across different embedding models.