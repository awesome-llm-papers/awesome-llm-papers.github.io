---
layout: publication
title: Evaluating The Quality Of Hallucination Benchmarks For Large Vision-language
  Models
authors: Yan et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: yan2024evaluating
citations: 136
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.17115'}]
tags: [RAG, EMNLP, GPT, Tools, Evaluation, Model Architecture, Multimodal Models,
  Datasets]
---
Despite the rapid progress and outstanding performance of Large
Vision-Language Models (LVLMs) in recent years, LVLMs have been plagued by the
issue of hallucination, i.e., LVLMs tend to generate responses that are
inconsistent with the corresponding visual inputs. To evaluate the degree of
hallucination in LVLMs, previous works have proposed a series of benchmarks
featuring different types of tasks and evaluation metrics. However, we find
that the quality of the existing hallucination benchmarks varies, with some
suffering from problems, e.g., inconsistent evaluation results under repeated
tests, and misalignment with human evaluation. To this end, we propose a
Hallucination benchmark Quality Measurement framework (HQM), which leverages
various indicators to assess the reliability and validity of existing
hallucination benchmarks separately. Specifically, for reliability we explore
test-retest reliability and parallel-forms reliability, while for validity we
examine criterion validity and coverage of hallucination types. Furthermore,
based on the results of our quality measurement, we construct a High-Quality
Hallucination Benchmark (HQH) for LVLMs, which demonstrates superior
reliability and validity under our HQM framework. We conduct an extensive
evaluation of over 10 representative LVLMs, including GPT-4o and
Gemini-1.5-Pro, to provide an in-depth analysis of the hallucination issues in
existing models. Our benchmark is publicly available at
https://github.com/HQHBench/HQHBench.