---
layout: publication
title: 'On NMT Search Errors And Model Errors: Cat Got Your Tongue?'
authors: Felix Stahlberg, Bill Byrne
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: stahlberg2019nmt
citations: 121
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.10090'}]
tags: ["EMNLP", "Evaluation"]
short_authors: Felix Stahlberg, Bill Byrne
---
We report on search errors and model errors in neural machine translation
(NMT). We present an exact inference procedure for neural sequence models based
on a combination of beam search and depth-first search. We use our exact search
to find the global best model scores under a Transformer base model for the
entire WMT15 English-German test set. Surprisingly, beam search fails to find
these global best model scores in most cases, even with a very large beam size
of 100. For more than 50% of the sentences, the model in fact assigns its
global best score to the empty translation, revealing a massive failure of
neural models in properly accounting for adequacy. We show by constraining
search with a minimum translation length that at the root of the problem of
empty translations lies an inherent bias towards shorter translations. We
conclude that vanilla NMT in its current form requires just the right amount of
beam search errors, which, from a modelling perspective, is a highly
unsatisfactory conclusion indeed, as the model often prefers an empty
translation.