---
layout: publication
title: Structural Adapters In Pretrained Language Models For Amr-to-text Generation
authors: Leonardo F. R. Ribeiro, Yue Zhang, Iryna Gurevych
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
citations: 18
bibkey: ribeiro2021structural
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.09120'}]
tags: [Language Modeling, Training Techniques]
---
Pretrained language models (PLM) have recently advanced graph-to-text
generation, where the input graph is linearized into a sequence and fed into
the PLM to obtain its representation. However, efficiently encoding the graph
structure in PLMs is challenging because such models were pretrained on natural
language, and modeling structured data may lead to catastrophic forgetting of
distributional knowledge. In this paper, we propose StructAdapt, an adapter
method to encode graph structure into PLMs. Contrary to prior work, StructAdapt
effectively models interactions among the nodes based on the graph
connectivity, only training graph structure-aware adapter parameters. In this
way, we incorporate task-specific knowledge while maintaining the topological
structure of the graph. We empirically show the benefits of explicitly encoding
graph structure into PLMs using StructAdapt, outperforming the state of the art
on two AMR-to-text datasets, training only 5.1% of the PLM parameters.