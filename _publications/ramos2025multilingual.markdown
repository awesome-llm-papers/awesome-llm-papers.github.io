---
layout: publication
title: Multilingual Contextualization Of Large Language Models For Document-level
  Machine Translation
authors: Ramos et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: ramos2025multilingual
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.12140'}]
tags: [RAG, EMNLP, Training Techniques, Prompting, Agentic, Reinforcement Learning,
  Fine Tuning]
---
Large language models (LLMs) have demonstrated strong performance in
sentence-level machine translation, but scaling to document-level translation
remains challenging, particularly in modeling long-range dependencies and
discourse phenomena across sentences and paragraphs. In this work, we propose a
method to improve LLM-based long-document translation through targeted
fine-tuning on high-quality document-level data, which we curate and introduce
as DocBlocks. Our approach supports multiple translation paradigms, including
direct document-to-document and chunk-level translation, by integrating
instructions both with and without surrounding context. This enables models to
better capture cross-sentence dependencies while maintaining strong
sentence-level translation performance. Experimental results show that
incorporating multiple translation paradigms improves document-level
translation quality and inference speed compared to prompting and agent-based
methods.