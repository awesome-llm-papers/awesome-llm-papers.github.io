---
layout: publication
title: 'MTAG: Modal-temporal Attention Graph For Unaligned Human Multimodal Language
  Sequences'
authors: Jianing Yang, Yongxin Wang, Ruitao Yi, Yuying Zhu, Azaan Rehman, Amir Zadeh,
  Soujanya Poria, Louis-philippe Morency
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: yang2020mtag
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.11985'}]
tags: ["Model Architecture", "NAACL", "Tools"]
short_authors: Yang et al.
---
Human communication is multimodal in nature; it is through multiple
modalities such as language, voice, and facial expressions, that opinions and
emotions are expressed. Data in this domain exhibits complex multi-relational
and temporal interactions. Learning from this data is a fundamentally
challenging research problem. In this paper, we propose Modal-Temporal
Attention Graph (MTAG). MTAG is an interpretable graph-based neural model that
provides a suitable framework for analyzing multimodal sequential data. We
first introduce a procedure to convert unaligned multimodal sequence data into
a graph with heterogeneous nodes and edges that captures the rich interactions
across modalities and through time. Then, a novel graph fusion operation,
called MTAG fusion, along with a dynamic pruning and read-out technique, is
designed to efficiently process this modal-temporal graph and capture various
interactions. By learning to focus only on the important interactions within
the graph, MTAG achieves state-of-the-art performance on multimodal sentiment
analysis and emotion recognition benchmarks, while utilizing significantly
fewer model parameters.