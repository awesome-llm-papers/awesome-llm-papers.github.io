---
layout: publication
title: Deep Contextualized Word Representations
authors: Peters et al.
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: peters2018deep
citations: 11009
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1802.05365'}]
tags: [Datasets, ACL]
---
We introduce a new type of deep contextualized word representation that
models both (1) complex characteristics of word use (e.g., syntax and
semantics), and (2) how these uses vary across linguistic contexts (i.e., to
model polysemy). Our word vectors are learned functions of the internal states
of a deep bidirectional language model (biLM), which is pre-trained on a large
text corpus. We show that these representations can be easily added to existing
models and significantly improve the state of the art across six challenging
NLP problems, including question answering, textual entailment and sentiment
analysis. We also present an analysis showing that exposing the deep internals
of the pre-trained network is crucial, allowing downstream models to mix
different types of semi-supervision signals.