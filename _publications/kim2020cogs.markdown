---
layout: publication
title: 'COGS: A Compositional Generalization Challenge Based On Semantic Interpretation'
authors: Kim Najoung, Linzen Tal
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: kim2020cogs
citations: 147
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05465'}]
tags: [RAG, EMNLP, Evaluation, Transformer, Model Architecture, Datasets]
---
Natural language is characterized by compositionality: the meaning of a
complex expression is constructed from the meanings of its constituent parts.
To facilitate the evaluation of the compositional abilities of language
processing architectures, we introduce COGS, a semantic parsing dataset based
on a fragment of English. The evaluation portion of COGS contains multiple
systematic gaps that can only be addressed by compositional generalization;
these include new combinations of familiar syntactic structures, or new
combinations of familiar words and familiar structures. In experiments with
Transformers and LSTMs, we found that in-distribution accuracy on the COGS test
set was near-perfect (96--99%), but generalization accuracy was substantially
lower (16--35%) and showed high sensitivity to random seed (\\(\pm\\)6--8%). These
findings indicate that contemporary standard NLP models are limited in their
compositional generalization capacity, and position COGS as a good way to
measure progress.