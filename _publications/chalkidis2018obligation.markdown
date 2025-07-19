---
layout: publication
title: Obligation And Prohibition Extraction Using Hierarchical Rnns
authors: Chalkidis Ilias, Androutsopoulos Ion, Michos Achilleas
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2018
bibkey: chalkidis2018obligation
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.03871'}]
tags: [ACL, Model Architecture, Transformer, Attention Mechanism]
---
We consider the task of detecting contractual obligations and prohibitions.
We show that a self-attention mechanism improves the performance of a BILSTM
classifier, the previous state of the art for this task, by allowing it to
focus on indicative tokens. We also introduce a hierarchical BILSTM, which
converts each sentence to an embedding, and processes the sentence embeddings
to classify each sentence. Apart from being faster to train, the hierarchical
BILSTM outperforms the flat one, even when the latter considers surrounding
sentences, because the hierarchical model has a broader discourse view.