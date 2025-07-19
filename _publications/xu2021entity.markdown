---
layout: publication
title: 'Entity Structure Within And Throughout: Modeling Mention Dependencies For
  Document-level Relation Extraction'
authors: Xu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: xu2021entity
citations: 144
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.10249'}]
tags: [Attention Mechanism, Alt, Ethics And Bias, Transformer, Model Architecture,
  AAAI, Datasets]
---
Entities, as the essential elements in relation extraction tasks, exhibit
certain structure. In this work, we formulate such structure as distinctive
dependencies between mention pairs. We then propose SSAN, which incorporates
these structural dependencies within the standard self-attention mechanism and
throughout the overall encoding stage. Specifically, we design two alternative
transformation modules inside each self-attention building block to produce
attentive biases so as to adaptively regularize its attention flow. Our
experiments demonstrate the usefulness of the proposed entity structure and the
effectiveness of SSAN. It significantly outperforms competitive baselines,
achieving new state-of-the-art results on three popular document-level relation
extraction datasets. We further provide ablation and visualization to show how
the entity structure guides the model for better relation extraction. Our code
is publicly available.