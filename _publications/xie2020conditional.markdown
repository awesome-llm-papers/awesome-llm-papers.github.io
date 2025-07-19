---
layout: publication
title: Conditional Self-attention For Query-based Summarization
authors: Xie et al.
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2020
bibkey: xie2020conditional
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.07338'}]
tags: [Model Architecture, Evaluation, ACL, Transformer, Datasets, Attention Mechanism]
---
Self-attention mechanisms have achieved great success on a variety of NLP
tasks due to its flexibility of capturing dependency between arbitrary
positions in a sequence. For problems such as query-based summarization (Qsumm)
and knowledge graph reasoning where each input sequence is associated with an
extra query, explicitly modeling such conditional contextual dependencies can
lead to a more accurate solution, which however cannot be captured by existing
self-attention mechanisms. In this paper, we propose \textit\{conditional
self-attention\} (CSA), a neural network module designed for conditional
dependency modeling. CSA works by adjusting the pairwise attention between
input tokens in a self-attention module with the matching score of the inputs
to the given query. Thereby, the contextual dependencies modeled by CSA will be
highly relevant to the query. We further studied variants of CSA defined by
different types of attention. Experiments on Debatepedia and HotpotQA benchmark
datasets show CSA consistently outperforms vanilla Transformer and previous
models for the Qsumm problem.