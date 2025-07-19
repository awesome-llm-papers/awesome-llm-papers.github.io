---
layout: publication
title: 'Fusionbench: A Comprehensive Benchmark Of Deep Model Fusion'
authors: Tang et al.
conference: Computers &amp; Security
year: 2024
bibkey: tang2024fusionbench
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.03280'}]
tags: [Training Techniques, Alt, Evaluation, Language Modeling, Security, Fine Tuning,
  Datasets, Merging]
---
Deep model fusion is an emerging technique that unifies the predictions or
parameters of several deep neural networks into a single model in a
cost-effective and data-efficient manner. This enables the unified model to
take advantage of the original models' strengths, potentially exceeding their
performance. Although a variety of deep model fusion techniques have been
introduced, their evaluations tend to be inconsistent and often inadequate to
validate their effectiveness and robustness against distribution shifts. To
address this issue, we introduce FusionBench, which is the first comprehensive
benchmark dedicated to deep model fusion. FusionBench covers a wide range of
tasks, including open-vocabulary image classification, text classification, and
text-to-text generation. Each category includes up to eight tasks with
corresponding task-specific models, featuring both full fine-tuning and LoRA
fine-tuning, as well as models of different sizes, to ensure fair and balanced
comparisons of various multi-task model fusion techniques across different
tasks, model scales, and fine-tuning strategies. We implement and evaluate a
broad spectrum of deep model fusion techniques. These techniques range from
model ensemble methods, which combine the predictions to improve the overall
performance, to model merging, which integrates different models into a single
one, and model mixing methods, which upscale or recombine the components of the
original models. FusionBench now contains 26 distinct tasks, 74 fine-tuned
models, and 16 fusion techniques, and we are committed to consistently
expanding the benchmark with more tasks, models, and fusion techniques. In
addition, we offer a well-documented set of resources and guidelines to aid
researchers in understanding and replicating the benchmark results. Homepage
https://github.com/tanganke/fusion_bench