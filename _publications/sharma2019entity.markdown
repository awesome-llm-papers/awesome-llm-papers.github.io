---
layout: publication
title: An Entity-driven Framework For Abstractive Summarization
authors: Eva Sharma, Luyang Huang, Zhe Hu, Lu Wang
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: sharma2019entity
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.02059'}]
tags: ["EMNLP"]
short_authors: Sharma et al.
---
Abstractive summarization systems aim to produce more coherent and concise
summaries than their extractive counterparts. Popular neural models have
achieved impressive results for single-document summarization, yet their
outputs are often incoherent and unfaithful to the input. In this paper, we
introduce SENECA, a novel System for ENtity-drivEn Coherent Abstractive
summarization framework that leverages entity information to generate
informative and coherent abstracts. Our framework takes a two-step approach:
(1) an entity-aware content selection module first identifies salient sentences
from the input, then (2) an abstract generation module conducts cross-sentence
information compression and abstraction to generate the final summary, which is
trained with rewards to promote coherence, conciseness, and clarity. The two
components are further connected using reinforcement learning. Automatic
evaluation shows that our model significantly outperforms previous
state-of-the-art on ROUGE and our proposed coherence measures on New York Times
and CNN/Daily Mail datasets. Human judges further rate our system summaries as
more informative and coherent than those by popular summarization models.