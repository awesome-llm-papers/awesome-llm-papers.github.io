---
layout: publication
title: How To Weight Multitask Finetuning? Fast Previews Via Bayesian Model-merging
authors: Maldonado et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2024
bibkey: maldonado2024how
citations: 124
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.08147'}]
tags: [Model Architecture, Merging, Training Techniques, ACL, Transformer, RAG, Alt]
---
When finetuning multiple tasks altogether, it is important to carefully weigh
them to get a good performance, but searching for good weights can be difficult
and costly. Here, we propose to aid the search with fast previews to quickly
get a rough idea of different reweighting options. We use model merging to
create previews by simply reusing and averaging parameters of models trained on
each task separately (no retraining required). To improve the quality of
previews, we propose a Bayesian approach to design new merging strategies by
using more flexible posteriors. We validate our findings on vision and
natural-language transformers. Our work shows the benefits of model merging via
Bayes to improve multitask finetuning.