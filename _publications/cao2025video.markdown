---
layout: publication
title: 'Video Simpleqa: Towards Factuality Evaluation In Large Video Language Models'
authors: Cao et al.
conference: 'Proceedings of the 62nd Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2025
bibkey: cao2025video
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.18923'}]
tags: [Tools, Efficiency And Optimization, Evaluation, ACL, RAG, Datasets, Reinforcement
    Learning]
---
Recent advancements in Large Video Language Models (LVLMs) have highlighted
their potential for multi-modal understanding, yet evaluating their factual
grounding in video contexts remains a critical unsolved challenge. To address
this gap, we introduce Video SimpleQA, the first comprehensive benchmark
tailored for factuality evaluation of LVLMs. Our work distinguishes from
existing video benchmarks through the following key features: 1) Knowledge
required: demanding integration of external knowledge beyond the explicit
narrative; 2) Fact-seeking question: targeting objective, undisputed events or
relationships, avoiding subjective interpretation; 3) Definitive & short-form
answer: Answers are crafted as unambiguous and definitively correct in a short
format, enabling automated evaluation through LLM-as-a-judge frameworks with
minimal scoring variance; 4) External-source verified: All annotations undergo
rigorous validation against authoritative external references to ensure the
reliability; 5) Temporal reasoning required: The annotated question types
encompass both static single-frame understanding and dynamic temporal
reasoning, explicitly evaluating LVLMs factuality under the long-context
dependencies. We extensively evaluate 41 state-of-the-art LVLMs and summarize
key findings as follows: 1) Current LVLMs exhibit notable deficiencies in
factual adherence, particularly for open-source models. The best-performing
model Gemini-1.5-Pro achieves merely an F-score of 54.4%; 2) Test-time compute
paradigms show insignificant performance gains, revealing fundamental
constraints for enhancing factuality through post-hoc computation; 3)
Retrieval-Augmented Generation demonstrates consistent improvements at the cost
of additional inference time overhead, presenting a critical
efficiency-performance trade-off.