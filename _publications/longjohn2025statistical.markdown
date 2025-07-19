---
layout: publication
title: Statistical Uncertainty Quantification For Aggregate Performance Metrics In
  Machine Learning Benchmarks
authors: Longjohn Rachel, Gopalan Giri, Casleton Emily
conference: Journal of Computational Physics
year: 2025
bibkey: longjohn2025statistical
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.04234'}]
tags: [RAG, Reinforcement Learning, Evaluation, Datasets]
---
Modern artificial intelligence is supported by machine learning models (e.g.,
foundation models) that are pretrained on a massive data corpus and then
adapted to solve a variety of downstream tasks. To summarize performance across
multiple tasks, evaluation metrics are often aggregated into a summary metric,
e.g., average accuracy across 10 question-answering tasks. When aggregating
evaluation metrics, it is useful to incorporate uncertainty in the aggregate
metric in order to gain a more realistic understanding of model performance.
Our objective in this work is to demonstrate how statistical methodology can be
used for quantifying uncertainty in metrics that have been aggregated across
multiple tasks. The methods we emphasize are bootstrapping, Bayesian
hierarchical (i.e., multilevel) modeling, and the visualization of task
weightings that consider standard errors. These techniques reveal insights such
as the dominance of a specific model for certain types of tasks despite an
overall poor performance. We use a popular ML benchmark, the Visual Task
Adaptation Benchmark (VTAB), to demonstrate the usefulness of our approaches.