---
layout: publication
title: Unified Pre-training For Program Understanding And Generation
authors: Wasi Uddin Ahmad, Saikat Chakraborty, Baishakhi Ray, Kai-wei Chang
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: ahmad2021unified
citations: 431
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.06333'}]
tags: ["Llm For Code", "Training Techniques"]
short_authors: Ahmad et al.
---
Code summarization and generation empower conversion between programming
language (PL) and natural language (NL), while code translation avails the
migration of legacy code from one PL to another. This paper introduces PLBART,
a sequence-to-sequence model capable of performing a broad spectrum of program
and language understanding and generation tasks. PLBART is pre-trained on an
extensive collection of Java and Python functions and associated NL text via
denoising autoencoding. Experiments on code summarization in the English
language, code generation, and code translation in seven programming languages
show that PLBART outperforms or rivals state-of-the-art models. Moreover,
experiments on discriminative tasks, e.g., program repair, clone detection, and
vulnerable code detection, demonstrate PLBART's effectiveness in program
understanding. Furthermore, analysis reveals that PLBART learns program syntax,
style (e.g., identifier naming convention), logical flow (e.g., if block inside
an else block is equivalent to else if block) that are crucial to program
semantics and thus excels even with limited annotations.