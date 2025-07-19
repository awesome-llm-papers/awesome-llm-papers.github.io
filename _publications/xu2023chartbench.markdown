---
layout: publication
title: 'Chartbench: A Benchmark For Complex Visual Reasoning In Charts'
authors: Xu et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2023
bibkey: xu2023chartbench
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.15915'}]
tags: [Fine Tuning, Training Techniques, Evaluation, ACL, RAG, Multimodal Models,
  Datasets]
---
Multimodal Large Language Models (MLLMs) have shown impressive capabilities
in image understanding and generation. However, current benchmarks fail to
accurately evaluate the chart comprehension of MLLMs due to limited chart types
and inappropriate metrics. To address this, we propose ChartBench, a
comprehensive benchmark designed to assess chart comprehension and data
reliability through complex visual reasoning. ChartBench includes 42
categories, 66.6k charts, and 600k question-answer pairs. Notably, many charts
lack data point annotations, which requires MLLMs to derive values similar to
human understanding by leveraging inherent chart elements such as color,
legends, and coordinate systems. We also design an enhanced evaluation metric,
Acc+, to evaluate MLLMs without extensive manual or costly LLM-based
evaluations. Furthermore, we propose two baselines based on the chain of
thought and supervised fine-tuning to improve model performance on unannotated
charts. Extensive experimental evaluations of 18 open-sourced and 3 proprietary
MLLMs reveal their limitations in chart comprehension and offer valuable
insights for further research. Code and dataset are publicly available at
https://chartbench.github.io.