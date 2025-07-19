---
layout: publication
title: 'APIRAT: Integrating Multi-source API Knowledge For Enhanced Code Translation
  With Llms'
authors: Wang et al.
conference: Proceedings of the Twenty-Seventh International Joint Conference on Artificial
  Intelligence
year: 2025
bibkey: wang2025apirat
citations: 159
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.14852'}]
tags: [Tools, Evaluation, LLM For Code, AAAI, IJCAI, Datasets, Reinforcement Learning]
---
Code translation is an essential task in software migration, multilingual
development, and system refactoring. Recent advancements in large language
models (LLMs) have demonstrated significant potential in this task. However,
prior studies have highlighted that LLMs often struggle with domain-specific
code, particularly in resolving cross-lingual API mappings. To tackle this
challenge, we propose APIRAT, a novel code translation method that integrates
multi-source API knowledge. APIRAT employs three API knowledge augmentation
techniques, including API sequence retrieval, API sequence back-translation,
and API mapping, to guide LLMs to translating code, ensuring both the correct
structure of API sequences and the accurate usage of individual APIs. Extensive
experiments on two public datasets, CodeNet and AVATAR, indicate that APIRAT
significantly surpasses existing LLM-based methods, achieving improvements in
computational accuracy ranging from 4% to 15.1%. Additionally, our evaluation
across different LLMs showcases the generalizability of APIRAT. An ablation
study further confirms the individual contributions of each API knowledge
component, underscoring the effectiveness of our approach.