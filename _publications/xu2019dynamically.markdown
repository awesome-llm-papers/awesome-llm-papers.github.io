---
layout: publication
title: Dynamically Pruned Message Passing Networks For Large-scale Knowledge Graph
  Reasoning
authors: Xu et al.
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: xu2019dynamically
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.11334'}]
tags: [Interpretability And Explainability, Attention Mechanism, Tools, CVPR, Transformer,
  Model Architecture]
---
We propose Dynamically Pruned Message Passing Networks (DPMPN) for
large-scale knowledge graph reasoning. In contrast to existing models,
embedding-based or path-based, we learn an input-dependent subgraph to
explicitly model reasoning process. Subgraphs are dynamically constructed and
expanded by applying graphical attention mechanism conditioned on input
queries. In this way, we not only construct graph-structured explanations but
also enable message passing designed in Graph Neural Networks (GNNs) to scale
with graph sizes. We take the inspiration from the consciousness prior proposed
by and develop a two-GNN framework to simultaneously encode input-agnostic full
graph representation and learn input-dependent local one coordinated by an
attention module. Experiments demonstrate the reasoning capability of our model
that is to provide clear graphical explanations as well as deliver accurate
predictions, outperforming most state-of-the-art methods in knowledge base
completion tasks.