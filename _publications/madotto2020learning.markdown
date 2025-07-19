---
layout: publication
title: Learning Knowledge Bases With Parameters For Task-oriented Dialogue Systems
authors: Madotto et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: madotto2020learning
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.13656'}]
tags: [Fine Tuning, Training Techniques, ACL, EMNLP, Datasets]
---
Task-oriented dialogue systems are either modularized with separate dialogue
state tracking (DST) and management steps or end-to-end trainable. In either
case, the knowledge base (KB) plays an essential role in fulfilling user
requests. Modularized systems rely on DST to interact with the KB, which is
expensive in terms of annotation and inference time. End-to-end systems use the
KB directly as input, but they cannot scale when the KB is larger than a few
hundred entries. In this paper, we propose a method to embed the KB, of any
size, directly into the model parameters. The resulting model does not require
any DST or template responses, nor the KB as input, and it can dynamically
update its KB via fine-tuning. We evaluate our solution in five task-oriented
dialogue datasets with small, medium, and large KB size. Our experiments show
that end-to-end models can effectively embed knowledge bases in their
parameters and achieve competitive performance in all evaluated datasets.