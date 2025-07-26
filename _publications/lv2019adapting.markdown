---
layout: publication
title: Adapting Meta Knowledge Graph Information For Multi-hop Reasoning Over Few-shot
  Relations
authors: Xin Lv, Yuxian Gu, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: lv2019adapting
citations: 76
additional_links: [{name: Code, url: 'https://github.com/'}, {name: Paper, url: 'https://arxiv.org/abs/1908.11513'}]
tags: ["EMNLP", "Few-Shot"]
short_authors: Lv et al.
---
Multi-hop knowledge graph (KG) reasoning is an effective and explainable
method for predicting the target entity via reasoning paths in query answering
(QA) task. Most previous methods assume that every relation in KGs has enough
training triples, regardless of those few-shot relations which cannot provide
sufficient triples for training robust reasoning models. In fact, the
performance of existing multi-hop reasoning methods drops significantly on
few-shot relations. In this paper, we propose a meta-based multi-hop reasoning
method (Meta-KGR), which adopts meta-learning to learn effective meta
parameters from high-frequency relations that could quickly adapt to few-shot
relations. We evaluate Meta-KGR on two public datasets sampled from Freebase
and NELL, and the experimental results show that Meta-KGR outperforms the
current state-of-the-art methods in few-shot scenarios. Our code and datasets
can be obtained from https://github.com/ THU-KEG/MetaKGR.