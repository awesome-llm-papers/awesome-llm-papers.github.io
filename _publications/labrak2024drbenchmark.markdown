---
layout: publication
title: 'Drbenchmark: A Large Language Understanding Evaluation Benchmark For French
  Biomedical Domain'
authors: Labrak et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2024
bibkey: labrak2024drbenchmark
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.13432'}]
tags: [Masked Language Model, BERT, Evaluation, ACL, Datasets, Alt]
---
The biomedical domain has sparked a significant interest in the field of
Natural Language Processing (NLP), which has seen substantial advancements with
pre-trained language models (PLMs). However, comparing these models has proven
challenging due to variations in evaluation protocols across different models.
A fair solution is to aggregate diverse downstream tasks into a benchmark,
allowing for the assessment of intrinsic PLMs qualities from various
perspectives. Although still limited to few languages, this initiative has been
undertaken in the biomedical field, notably English and Chinese. This
limitation hampers the evaluation of the latest French biomedical models, as
they are either assessed on a minimal number of tasks with non-standardized
protocols or evaluated using general downstream tasks. To bridge this research
gap and account for the unique sensitivities of French, we present the
first-ever publicly available French biomedical language understanding
benchmark called DrBenchmark. It encompasses 20 diversified tasks, including
named-entity recognition, part-of-speech tagging, question-answering, semantic
textual similarity, and classification. We evaluate 8 state-of-the-art
pre-trained masked language models (MLMs) on general and biomedical-specific
data, as well as English specific MLMs to assess their cross-lingual
capabilities. Our experiments reveal that no single model excels across all
tasks, while generalist models are sometimes still competitive.