---
layout: publication
title: Modeling Global And Local Node Contexts For Text Generation From Knowledge
  Graphs
authors: Leonardo F. R. Ribeiro, Yue Zhang, Claire Gardent, Iryna Gurevych
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: ribeiro2020modeling
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.11003'}]
tags: ["Datasets", "TACL"]
short_authors: Ribeiro et al.
---
Recent graph-to-text models generate text from graph-based data using either
global or local aggregation to learn node representations. Global node encoding
allows explicit communication between two distant nodes, thereby neglecting
graph topology as all nodes are directly connected. In contrast, local node
encoding considers the relations between neighbor nodes capturing the graph
structure, but it can fail to capture long-range relations. In this work, we
gather both encoding strategies, proposing novel neural models which encode an
input graph combining both global and local node contexts, in order to learn
better contextualized node embeddings. In our experiments, we demonstrate that
our approaches lead to significant improvements on two graph-to-text datasets
achieving BLEU scores of 18.01 on AGENDA dataset, and 63.69 on the WebNLG
dataset for seen categories, outperforming state-of-the-art models by 3.7 and
3.1 points, respectively.