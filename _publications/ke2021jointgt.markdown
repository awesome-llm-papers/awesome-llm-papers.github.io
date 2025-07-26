---
layout: publication
title: 'Jointgt: Graph-text Joint Representation Learning For Text Generation From
  Knowledge Graphs'
authors: Pei Ke, Haozhe Ji, Yu Ran, Xin Cui, Liwei Wang, Linfeng Song, Xiaoyan Zhu,
  Minlie Huang
conference: 'Findings of the Association for Computational Linguistics: ACL-IJCNLP
  2021'
year: 2021
bibkey: ke2021jointgt
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.10502'}]
tags: ["Model Architecture"]
short_authors: Ke et al.
---
Existing pre-trained models for knowledge-graph-to-text (KG-to-text)
generation simply fine-tune text-to-text pre-trained models such as BART or T5
on KG-to-text datasets, which largely ignore the graph structure during
encoding and lack elaborate pre-training tasks to explicitly model graph-text
alignments. To tackle these problems, we propose a graph-text joint
representation learning model called JointGT. During encoding, we devise a
structure-aware semantic aggregation module which is plugged into each
Transformer layer to preserve the graph structure. Furthermore, we propose
three new pre-training tasks to explicitly enhance the graph-text alignment
including respective text / graph reconstruction, and graph-text alignment in
the embedding space via Optimal Transport. Experiments show that JointGT
obtains new state-of-the-art performance on various KG-to-text datasets.