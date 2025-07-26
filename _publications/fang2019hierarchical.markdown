---
layout: publication
title: Hierarchical Graph Network For Multi-hop Question Answering
authors: Yuwei Fang, Siqi Sun, Zhe Gan, Rohit Pillai, Shuohang Wang, Jingjing Liu
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: fang2019hierarchical
citations: 154
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03631'}]
tags: ["EMNLP"]
short_authors: Fang et al.
---
In this paper, we present Hierarchical Graph Network (HGN) for multi-hop
question answering. To aggregate clues from scattered texts across multiple
paragraphs, a hierarchical graph is created by constructing nodes on different
levels of granularity (questions, paragraphs, sentences, entities), the
representations of which are initialized with pre-trained contextual encoders.
Given this hierarchical graph, the initial node representations are updated
through graph propagation, and multi-hop reasoning is performed via traversing
through the graph edges for each subsequent sub-task (e.g., paragraph
selection, supporting facts extraction, answer prediction). By weaving
heterogeneous nodes into an integral unified graph, this hierarchical
differentiation of node granularity enables HGN to support different question
answering sub-tasks simultaneously. Experiments on the HotpotQA benchmark
demonstrate that the proposed model achieves new state of the art,
outperforming existing multi-hop QA approaches.