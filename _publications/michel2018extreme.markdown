---
layout: publication
title: Extreme Adaptation For Personalized Neural Machine Translation
authors: Paul Michel, Graham Neubig
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2018
bibkey: michel2018extreme
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.01817'}]
tags: ["Ethics & Fairness"]
short_authors: Paul Michel, Graham Neubig
---
Every person speaks or writes their own flavor of their native language,
influenced by a number of factors: the content they tend to talk about, their
gender, their social status, or their geographical origin.
  When attempting to perform Machine Translation (MT), these variations have a
significant effect on how the system should perform translation, but this is
not captured well by standard one-size-fits-all models.
  In this paper, we propose a simple and parameter-efficient adaptation
technique that only requires adapting the bias of the output softmax to each
particular user of the MT system, either directly or through a factored
approximation.
  Experiments on TED talks in three languages demonstrate improvements in
translation accuracy, and better reflection of speaker traits in the target
text.