---
layout: publication
title: Learning Contextual Representations For Semantic Parsing With Generation-augmented
  Pre-training
authors: Shi et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: shi2020learning
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.10309'}]
tags: [RAG, Training Techniques, Masked Language Model, Tools, Evaluation, BERT, AAAI,
  Datasets]
---
Most recently, there has been significant interest in learning contextual
representations for various NLP tasks, by leveraging large scale text corpora
to train large neural language models with self-supervised learning objectives,
such as Masked Language Model (MLM). However, based on a pilot study, we
observe three issues of existing general-purpose language models when they are
applied to text-to-SQL semantic parsers: fail to detect column mentions in the
utterances, fail to infer column mentions from cell values, and fail to compose
complex SQL queries. To mitigate these issues, we present a model pre-training
framework, Generation-Augmented Pre-training (GAP), that jointly learns
representations of natural language utterances and table schemas by leveraging
generation models to generate pre-train data. GAP MODEL is trained on 2M
utterance-schema pairs and 30K utterance-schema-SQL triples, whose utterances
are produced by generative models. Based on experimental results, neural
semantic parsers that leverage GAP MODEL as a representation encoder obtain new
state-of-the-art results on both SPIDER and CRITERIA-TO-SQL benchmarks.