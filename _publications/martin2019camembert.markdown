---
layout: publication
title: 'Camembert: A Tasty French Language Model'
authors: "Louis Martin, Benjamin Muller, Pedro Javier Ortiz Su\xE1rez, Yoann Dupont,\
  \ Laurent Romary, \xC9ric Villemonte de La Clergerie, Djam\xE9 Seddah, Beno\xEE\
  t Sagot"
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: martin2019camembert
citations: 412
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03894'}]
tags: ["Model Architecture"]
short_authors: Martin et al.
---
Pretrained language models are now ubiquitous in Natural Language Processing.
Despite their success, most available models have either been trained on
English data or on the concatenation of data in multiple languages. This makes
practical use of such models --in all languages except English-- very limited.
In this paper, we investigate the feasibility of training monolingual
Transformer-based language models for other languages, taking French as an
example and evaluating our language models on part-of-speech tagging,
dependency parsing, named entity recognition and natural language inference
tasks. We show that the use of web crawled data is preferable to the use of
Wikipedia data. More surprisingly, we show that a relatively small web crawled
dataset (4GB) leads to results that are as good as those obtained using larger
datasets (130+GB). Our best performing model CamemBERT reaches or improves the
state of the art in all four downstream tasks.