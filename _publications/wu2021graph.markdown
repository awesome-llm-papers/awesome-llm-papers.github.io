---
layout: publication
title: 'Graph-free Multi-hop Reading Comprehension: A Select-to-guide Strategy'
authors: Wu Bohong, Zhang Zhuosheng, Zhao Hai
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2021
bibkey: wu2021graph
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.11823'}]
tags: [Model Architecture, Interpretability And Explainability, Evaluation, ACL, RAG,
  Transformer, Datasets, Reinforcement Learning, Attention Mechanism, Alt]
---
Multi-hop reading comprehension (MHRC) requires not only to predict the
correct answer span in the given passage, but also to provide a chain of
supporting evidences for reasoning interpretability. It is natural to model
such a process into graph structure by understanding multi-hop reasoning as
jumping over entity nodes, which has made graph modelling dominant on this
task. Recently, there have been dissenting voices about whether graph modelling
is indispensable due to the inconvenience of the graph building, however
existing state-of-the-art graph-free attempts suffer from huge performance gap
compared to graph-based ones. This work presents a novel graph-free alternative
which firstly outperform all graph models on MHRC. In detail, we exploit a
select-to-guide (S2G) strategy to accurately retrieve evidence paragraphs in a
coarse-to-fine manner, incorporated with two novel attention mechanisms, which
surprisingly shows conforming to the nature of multi-hop reasoning. Our
graph-free model achieves significant and consistent performance gain over
strong baselines and the current new state-of-the-art on the MHRC benchmark,
HotpotQA, among all the published works.