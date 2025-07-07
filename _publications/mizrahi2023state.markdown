---
layout: publication
title: State Of What Art? A Call For Multi-prompt LLM Evaluation
authors: Moran Mizrahi et al.
conference: Arxiv
year: 2023
citations: 28
bibkey: mizrahi2023state
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.00595'}]
tags: [Applications, Security, Prompting]
---
Recent advances in large language models (LLMs) have led to the development
of various evaluation benchmarks. These benchmarks typically rely on a single
instruction template for evaluating all LLMs on a specific task. In this paper,
we comprehensively analyze the brittleness of results obtained via
single-prompt evaluations across 6.5M instances, involving 20 different LLMs
and 39 tasks from 3 benchmarks. To improve robustness of the analysis, we
propose to evaluate LLMs with a set of diverse prompts instead. We discuss
tailored evaluation metrics for specific use cases (e.g., LLM developers vs.
developers interested in a specific downstream task), ensuring a more reliable
and meaningful assessment of LLM capabilities. We then implement these criteria
and conduct evaluations of multiple models, providing insights into the true
strengths and limitations of current LLMs.