---
layout: publication
title: Prompt-based Depth Pruning Of Large Language Models
authors: Wee Juyun, Park Minjae, Lee Jaeho
conference: CHI Conference on Human Factors in Computing Systems Extended Abstracts
year: 2025
bibkey: wee2025prompt
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.04348'}]
tags: [Training Techniques, Prompting, Evaluation, Transformer, Model Architecture,
  Efficiency And Optimization, Pruning, Datasets]
---
Depth pruning aims to reduce the inference cost of a large language model without any hardware-specific complications, by simply removing several less important transformer blocks. However, our empirical findings suggest that the importance of a transformer block may be highly task-dependent -- a block that is crucial for a task can be removed without degrading the accuracy on another task. Based on this observation, we develop a dynamic depth pruning algorithm, coined PuDDing (Prompt-routed Dynamic Depth Pruning), which determines which blocks to omit from the model based on the input prompt. PuDDing operates by training a lightweight router to predict the best omission set among a set of options, where this option set has also been constructed in a data-driven manner. Empirical results on commonsense reasoning benchmarks demonstrate that PuDDing effectively accelerates the inference language models, and achieves better on-task performance than static depth pruning baselines.