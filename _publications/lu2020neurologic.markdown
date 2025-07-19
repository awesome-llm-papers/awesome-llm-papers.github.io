---
layout: publication
title: 'Neurologic Decoding: (un)supervised Neural Text Generation With Predicate
  Logic Constraints'
authors: Lu et al.
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2020
bibkey: lu2020neurologic
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.12884'}]
tags: [Training Techniques, Evaluation, ACL, NAACL, Datasets, Reinforcement Learning,
  Language Modeling]
---
Conditional text generation often requires lexical constraints, i.e., which
words should or shouldn't be included in the output text. While the dominant
recipe for conditional text generation has been large-scale pretrained language
models that are finetuned on the task-specific training data, such models do
not learn to follow the underlying constraints reliably, even when supervised
with large amounts of task-specific examples.
  We propose NeuroLogic Decoding, a simple yet effective algorithm that enables
neural language models -- supervised or not -- to generate fluent text while
satisfying complex lexical constraints. Our approach is powerful yet efficient.
It handles any set of lexical constraints that is expressible under predicate
logic, while its asymptotic runtime is equivalent to conventional beam search.
  Empirical results on four benchmarks show that NeuroLogic Decoding
outperforms previous approaches, including algorithms that handle a subset of
our constraints. Moreover, we find that unsupervised models with NeuroLogic
Decoding often outperform supervised models with conventional decoding, even
when the latter is based on considerably larger networks. Our results suggest
the limit of large-scale neural networks for fine-grained controllable
generation and the promise of inference-time algorithms.