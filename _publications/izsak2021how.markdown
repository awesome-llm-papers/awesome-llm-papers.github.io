---
layout: publication
title: How To Train BERT With An Academic Budget
authors: Peter Izsak, Moshe Berchansky, Omer Levy
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: izsak2021how
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.07705'}]
tags: ["Model Architecture"]
short_authors: Peter Izsak, Moshe Berchansky, Omer Levy
---
While large language models a la BERT are used ubiquitously in NLP,
pretraining them is considered a luxury that only a few well-funded industry
labs can afford. How can one train such models with a more modest budget? We
present a recipe for pretraining a masked language model in 24 hours using a
single low-end deep learning server. We demonstrate that through a combination
of software optimizations, design choices, and hyperparameter tuning, it is
possible to produce models that are competitive with BERT-base on GLUE tasks at
a fraction of the original pretraining cost.