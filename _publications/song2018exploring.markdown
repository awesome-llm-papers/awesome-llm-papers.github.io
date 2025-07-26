---
layout: publication
title: Exploring Graph-structured Passage Representation For Multi-hop Reading Comprehension
  With Graph Neural Networks
authors: Linfeng Song, Zhiguo Wang, Mo Yu, Yue Zhang, Radu Florian, Daniel Gildea
conference: Arxiv
year: 2018
bibkey: song2018exploring
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.02040'}]
tags: ["Datasets"]
short_authors: Song et al.
---
Multi-hop reading comprehension focuses on one type of factoid question,
where a system needs to properly integrate multiple pieces of evidence to
correctly answer a question. Previous work approximates global evidence with
local coreference information, encoding coreference chains with DAG-styled GRU
layers within a gated-attention reader. However, coreference is limited in
providing information for rich inference. We introduce a new method for better
connecting global evidence, which forms more complex graphs compared to DAGs.
To perform evidence integration on our graphs, we investigate two recent graph
neural networks, namely graph convolutional network (GCN) and graph recurrent
network (GRN). Experiments on two standard datasets show that richer global
information leads to better answers. Our method performs better than all
published results on these datasets.