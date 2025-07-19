---
layout: publication
title: Extracting Multiple-relations In One-pass With Pre-trained Transformers
authors: Wang et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: wang2019extracting
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.01030'}]
tags: [Model Architecture, Evaluation, ACL, Transformer, RAG, Datasets, Attention
    Mechanism]
---
Most approaches to extraction multiple relations from a paragraph require
multiple passes over the paragraph. In practice, multiple passes are
computationally expensive and this makes difficult to scale to longer
paragraphs and larger text corpora. In this work, we focus on the task of
multiple relation extraction by encoding the paragraph only once (one-pass). We
build our solution on the pre-trained self-attentive (Transformer) models,
where we first add a structured prediction layer to handle extraction between
multiple entity pairs, then enhance the paragraph embedding to capture multiple
relational information associated with each entity with an entity-aware
attention technique. We show that our approach is not only scalable but can
also perform state-of-the-art on the standard benchmark ACE 2005.