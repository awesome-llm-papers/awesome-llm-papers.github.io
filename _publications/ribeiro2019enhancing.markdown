---
layout: publication
title: Enhancing Amr-to-text Generation With Dual Graph Representations
authors: Leonardo F. R. Ribeiro, Claire Gardent, Iryna Gurevych
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: ribeiro2019enhancing
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00352'}]
tags: ["EMNLP"]
short_authors: Leonardo F. R. Ribeiro, Claire Gardent, Iryna Gurevych
---
Generating text from graph-based data, such as Abstract Meaning
Representation (AMR), is a challenging task due to the inherent difficulty in
how to properly encode the structure of a graph with labeled edges. To address
this difficulty, we propose a novel graph-to-sequence model that encodes
different but complementary perspectives of the structural information
contained in the AMR graph. The model learns parallel top-down and bottom-up
representations of nodes capturing contrasting views of the graph. We also
investigate the use of different node message passing strategies, employing
different state-of-the-art graph encoders to compute node representations based
on incoming and outgoing perspectives. In our experiments, we demonstrate that
the dual graph representation leads to improvements in AMR-to-text generation,
achieving state-of-the-art results on two AMR datasets.