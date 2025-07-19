---
layout: publication
title: 'Mediator: Memory-efficient LLM Merging With Less Parameter Conflicts And Uncertainty
  Based Routing'
authors: Lai et al.
conference: IEEE Transactions on Computers
year: 2025
bibkey: lai2025mediator
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.04411'}]
tags: [RAG, Reinforcement Learning, Merging]
---
Model merging aggregates Large Language Models (LLMs) finetuned on different
tasks into a stronger one. However, parameter conflicts between models leads to
performance degradation in averaging. While model routing addresses this issue
by selecting individual models during inference, it imposes excessive storage
and compute costs, and fails to leverage the common knowledge from different
models. In this work, we observe that different layers exhibit varying levels
of parameter conflicts. Building on this insight, we average layers with
minimal parameter conflicts and use a novel task-level expert routing for
layers with significant conflicts. To further reduce storage costs, inspired by
task arithmetic sparsity, we decouple multiple fine-tuned experts into a dense
expert and several sparse experts. Considering the out-of-distribution samples,
we select and merge appropriate experts based on the task uncertainty of the
input data. We conduct extensive experiments on both LLaMA and Qwen with
varying parameter scales, and evaluate on real-world reasoning tasks. Results
demonstrate that our method consistently achieves significant performance
improvements while requiring less system cost compared to existing methods.