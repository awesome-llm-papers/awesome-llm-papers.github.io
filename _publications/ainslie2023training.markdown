---
layout: publication
title: 'GQA: Training Generalized Multi-query Transformer Models From Multi-head Checkpoints'
authors: Joshua Ainslie et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
citations: 118
bibkey: ainslie2023training
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.13245'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Pre-Training, Training
    Techniques]
---
Multi-query attention (MQA), which only uses a single key-value head,
drastically speeds up decoder inference. However, MQA can lead to quality
degradation, and moreover it may not be desirable to train a separate model
just for faster inference. We (1) propose a recipe for uptraining existing
multi-head language model checkpoints into models with MQA using 5% of original
pre-training compute, and (2) introduce grouped-query attention (GQA), a
generalization of multi-query attention which uses an intermediate (more than
one, less than number of query heads) number of key-value heads. We show that
uptrained GQA achieves quality close to multi-head attention with comparable
speed to MQA.