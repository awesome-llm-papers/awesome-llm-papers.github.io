---
layout: publication
title: Rapid Adaptation Of Neural Machine Translation To New Languages
authors: Graham Neubig, Junjie Hu
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: neubig2018rapid
citations: 209
additional_links: [{name: Code, url: 'https://github.com/neubig/rapid-adaptation'},
  {name: Paper, url: 'https://arxiv.org/abs/1808.04189'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Graham Neubig, Junjie Hu
---
This paper examines the problem of adapting neural machine translation
systems to new, low-resourced languages (LRLs) as effectively and rapidly as
possible. We propose methods based on starting with massively multilingual
"seed models", which can be trained ahead-of-time, and then continuing training
on data related to the LRL. We contrast a number of strategies, leading to a
novel, simple, yet effective method of "similar-language regularization", where
we jointly train on both a LRL of interest and a similar high-resourced
language to prevent over-fitting to small LRL data. Experiments demonstrate
that massively multilingual models, even without any explicit adaptation, are
surprisingly effective, achieving BLEU scores of up to 15.5 with no data from
the LRL, and that the proposed similar-language regularization method improves
over other adaptation methods by 1.7 BLEU points average over 4 LRL settings.
Code to reproduce experiments at https://github.com/neubig/rapid-adaptation