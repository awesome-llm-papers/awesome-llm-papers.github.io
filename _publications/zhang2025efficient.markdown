---
layout: publication
title: Efficient Tuning Of Large Language Models For Knowledge-grounded Dialogue Generation
authors: Zhang et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2025
bibkey: zhang2025efficient
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.07754'}]
tags: [Training Techniques, EMNLP, Evaluation, Fine Tuning, Datasets]
---
Large language models (LLMs) demonstrate remarkable text comprehension and
generation capabilities but often lack the ability to utilize up-to-date or
domain-specific knowledge not included in their training data. To address this
gap, we introduce KEDiT, an efficient method for fine-tuning LLMs for
knowledge-grounded dialogue generation. KEDiT operates in two main phases:
first, it employs an information bottleneck to compress retrieved knowledge
into learnable parameters, retaining essential information while minimizing
computational overhead. Second, a lightweight knowledge-aware adapter
integrates these compressed knowledge vectors into the LLM during fine-tuning,
updating less than 2% of the model parameters. The experimental results on the
Wizard of Wikipedia and a newly constructed PubMed-Dialog dataset demonstrate
that KEDiT excels in generating contextually relevant and informative
responses, outperforming competitive baselines in automatic, LLM-based, and
human evaluations. This approach effectively combines the strengths of
pretrained LLMs with the adaptability needed for incorporating dynamic
knowledge, presenting a scalable solution for fields such as medicine.