---
layout: publication
title: A Comprehensive Analysis For Visual Object Hallucination In Large Vision-language
  Models
authors: Jing et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: jing2025comprehensive
citations: 136
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.01958'}]
tags: [EMNLP, Responsible AI, Evaluation, Reinforcement Learning, Multimodal Models,
  Datasets]
---
Large Vision-Language Models (LVLMs) demonstrate remarkable capabilities in
multimodal tasks, but visual object hallucination remains a persistent issue.
It refers to scenarios where models generate inaccurate visual object-related
information based on the query input, potentially leading to misinformation and
concerns about safety and reliability. Previous works focus on the evaluation
and mitigation of visual hallucinations, but the underlying causes have not
been comprehensively investigated. In this paper, we analyze each component of
LLaVA-like LVLMs -- the large language model, the vision backbone, and the
projector -- to identify potential sources of error and their impact. Based on
our observations, we propose methods to mitigate hallucination for each
problematic component. Additionally, we developed two hallucination benchmarks:
QA-VisualGenome, which emphasizes attribute and relation hallucinations, and
QA-FB15k, which focuses on cognition-based hallucinations.