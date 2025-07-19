---
layout: publication
title: 'KELM: Knowledge Enhanced Pre-trained Language Representations With Message
  Passing On Hierarchical Relational Graphs'
authors: Lu et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2021
bibkey: lu2021kelm
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04223'}]
tags: [Training Techniques, EMNLP, Tools, BERT, Model Architecture, Reinforcement
    Learning, Fine Tuning, Datasets, Merging]
---
Incorporating factual knowledge into pre-trained language models (PLM) such
as BERT is an emerging trend in recent NLP studies. However, most of the
existing methods combine the external knowledge integration module with a
modified pre-training loss and re-implement the pre-training process on the
large-scale corpus. Re-pretraining these models is usually resource-consuming,
and difficult to adapt to another domain with a different knowledge graph (KG).
Besides, those works either cannot embed knowledge context dynamically
according to textual context or struggle with the knowledge ambiguity issue. In
this paper, we propose a novel knowledge-aware language model framework based
on fine-tuning process, which equips PLM with a unified knowledge-enhanced text
graph that contains both text and multi-relational sub-graphs extracted from
KG. We design a hierarchical relational-graph-based message passing mechanism,
which can allow the representations of injected KG and text to mutually update
each other and can dynamically select ambiguous mentioned entities that share
the same text. Our empirical results show that our model can efficiently
incorporate world knowledge from KGs into existing language models such as
BERT, and achieve significant improvement on the machine reading comprehension
(MRC) task compared with other knowledge-enhanced models.