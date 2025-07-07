---
layout: publication
title: Sequence-to-sequence Learning For Task-oriented Dialogue With Dialogue State
  Representation
authors: Haoyang Wen, Yijia Liu, Wanxiang Che, Libo Qin, Ting Liu
conference: Arxiv
year: 2018
citations: 32
bibkey: wen2018sequence
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.04441'}]
tags: [Transformer, RAG, Attention Mechanism, Tools, Model Architecture]
---
Classic pipeline models for task-oriented dialogue system require explicit
modeling the dialogue states and hand-crafted action spaces to query a
domain-specific knowledge base. Conversely, sequence-to-sequence models learn
to map dialogue history to the response in current turn without explicit
knowledge base querying. In this work, we propose a novel framework that
leverages the advantages of classic pipeline and sequence-to-sequence models.
Our framework models a dialogue state as a fixed-size distributed
representation and use this representation to query a knowledge base via an
attention mechanism. Experiment on Stanford Multi-turn Multi-domain
Task-oriented Dialogue Dataset shows that our framework significantly
outperforms other sequence-to-sequence based baseline models on both automatic
and human evaluation.