---
layout: publication
title: Chains Of Reasoning Over Entities, Relations, And Text Using Recurrent Neural
  Networks
authors: Das et al.
conference: 'Proceedings of the 15th Conference of the European Chapter of the Association
  for Computational Linguistics: Volume 1, Long Papers'
year: 2016
bibkey: das2016chains
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1607.01426'}]
tags: [ACL, Model Architecture, Reinforcement Learning, Attention Mechanism]
---
Our goal is to combine the rich multistep inference of symbolic logical
reasoning with the generalization capabilities of neural networks. We are
particularly interested in complex reasoning about entities and relations in
text and large-scale knowledge bases (KBs). Neelakantan et al. (2015) use RNNs
to compose the distributed semantics of multi-hop paths in KBs; however for
multiple reasons, the approach lacks accuracy and practicality. This paper
proposes three significant modeling advances: (1) we learn to jointly reason
about relations, entities, and entity-types; (2) we use neural attention
modeling to incorporate multiple paths; (3) we learn to share strength in a
single RNN that represents logical composition across all relations. On a
largescale Freebase+ClueWeb prediction task, we achieve 25% error reduction,
and a 53% error reduction on sparse relations due to shared strength. On chains
of reasoning in WordNet we reduce error in mean quantile by 84% versus previous
state-of-the-art. The code and data are available at
https://rajarshd.github.io/ChainsofReasoning