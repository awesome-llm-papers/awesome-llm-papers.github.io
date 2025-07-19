---
layout: publication
title: 'Bi-link: Bridging Inductive Link Predictions From Text Via Contrastive Learning
  Of Transformers And Prompts'
authors: Peng Bohua, Liang Shihao, Islam Mobarakol
conference: Proceedings of the Web Conference 2021
year: 2022
bibkey: peng2022bi
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.14463'}]
tags: [Prompting, Tools, BERT, Transformer, Model Architecture, Reinforcement Learning,
  Datasets]
---
Inductive knowledge graph completion requires models to comprehend the
underlying semantics and logic patterns of relations. With the advance of
pretrained language models, recent research have designed transformers for link
prediction tasks. However, empirical studies show that linearizing triples
affects the learning of relational patterns, such as inversion and symmetry. In
this paper, we propose Bi-Link, a contrastive learning framework with
probabilistic syntax prompts for link predictions. Using grammatical knowledge
of BERT, we efficiently search for relational prompts according to learnt
syntactical patterns that generalize to large knowledge graphs. To better
express symmetric relations, we design a symmetric link prediction model,
establishing bidirectional linking between forward prediction and backward
prediction. This bidirectional linking accommodates flexible self-ensemble
strategies at test time. In our experiments, Bi-Link outperforms recent
baselines on link prediction datasets (WN18RR, FB15K-237, and Wikidata5M).
Furthermore, we construct Zeshel-Ind as an in-domain inductive entity linking
the environment to evaluate Bi-Link. The experimental results demonstrate that
our method yields robust representations which can generalize under domain
shift.