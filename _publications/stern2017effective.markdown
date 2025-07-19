---
layout: publication
title: Effective Inference For Generative Neural Parsing
authors: Stern Mitchell, Fried Daniel, Klein Dan
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: stern2017effective
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.08976'}]
tags: [Pruning, EMNLP, Efficiency And Optimization, Alt]
---
Generative neural models have recently achieved state-of-the-art results for
constituency parsing. However, without a feasible search procedure, their use
has so far been limited to reranking the output of external parsers in which
decoding is more tractable. We describe an alternative to the conventional
action-level beam search used for discriminative neural models that enables us
to decode directly in these generative models. We then show that by improving
our basic candidate selection strategy and using a coarse pruning function, we
can improve accuracy while exploring significantly less of the search space.
Applied to the model of Choe and Charniak (2016), our inference procedure
obtains 92.56 F1 on section 23 of the Penn Treebank, surpassing prior
state-of-the-art results for single-model systems.