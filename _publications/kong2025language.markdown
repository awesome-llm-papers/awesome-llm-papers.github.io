---
layout: publication
title: 'Language-tpp: Integrating Temporal Point Processes With Language Models For
  Event Analysis'
authors: Kong et al.
conference: Proceedings of the ACL 2014 Workshop on Language Technologies and Computational
  Social Science
year: 2025
bibkey: kong2025language
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.07139'}]
tags: [Model Architecture, Tools, Time Series, ACL, Datasets]
---
Temporal Point Processes (TPPs) have been widely used for event sequence
modeling, but they often struggle to incorporate rich textual event
descriptions effectively. Conversely, while Large Language Models (LLMs) have
been shown remarkable capabilities in processing textual data, they lack
mechanisms for handling temporal dynamics. To bridge this gap, we introduce
Language-TPP, a unified framework that integrates TPPs with LLMs for enhanced
event sequence modeling. Language-TPP introduces a novel temporal encoding
mechanism that converts continuous time intervals into specialized byte-tokens,
enabling seamless integration with standard LLM architectures. This approach
allows Language-TPP to achieve state-of-the-art performance across multiple TPP
tasks, including event time prediction, type prediction, and intensity
estimation, on five datasets. Additionally, we demonstrate that incorporating
temporal information significantly improves the quality of generated event
descriptions.