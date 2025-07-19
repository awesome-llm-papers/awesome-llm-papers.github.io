---
layout: publication
title: Gated-attention Readers For Text Comprehension
authors: Dhingra et al.
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2016
bibkey: dhingra2016gated
citations: 357
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.01549'}]
tags: [Model Architecture, Evaluation, ACL, Transformer, Datasets, Attention Mechanism,
  Alt]
---
In this paper we study the problem of answering cloze-style questions over
documents. Our model, the Gated-Attention (GA) Reader, integrates a multi-hop
architecture with a novel attention mechanism, which is based on multiplicative
interactions between the query embedding and the intermediate states of a
recurrent neural network document reader. This enables the reader to build
query-specific representations of tokens in the document for accurate answer
selection. The GA Reader obtains state-of-the-art results on three benchmarks
for this task--the CNN \& Daily Mail news stories and the Who Did What dataset.
The effectiveness of multiplicative interaction is demonstrated by an ablation
study, and by comparing to alternative compositional operators for implementing
the gated-attention. The code is available at
https://github.com/bdhingra/ga-reader.