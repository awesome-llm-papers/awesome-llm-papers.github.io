---
layout: publication
title: Graph-based Neural Sentence Ordering
authors: Yin et al.
conference: Proceedings of the Twenty-Eighth International Joint Conference on Artificial
  Intelligence
year: 2019
bibkey: yin2019graph
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.07225'}]
tags: [Evaluation, AAAI, RAG, IJCAI, Datasets]
---
Sentence ordering is to restore the original paragraph from a set of
sentences. It involves capturing global dependencies among sentences regardless
of their input order. In this paper, we propose a novel and flexible
graph-based neural sentence ordering model, which adopts graph recurrent
network \cite\{Zhang:acl18\} to accurately learn semantic representations of the
sentences. Instead of assuming connections between all pairs of input
sentences, we use entities that are shared among multiple sentences to make
more expressive graph representations with less noise. Experimental results
show that our proposed model outperforms the existing state-of-the-art systems
on several benchmark datasets, demonstrating the effectiveness of our model. We
also conduct a thorough analysis on how entities help the performance.