---
layout: publication
title: 'The Bottom-up Evolution Of Representations In The Transformer: A Study With
  Machine Translation And Language Modeling Objectives'
authors: Elena Voita, Rico Sennrich, Ivan Titov
conference: Arxiv
year: 2019
citations: 24
bibkey: voita2019bottom
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.01380'}]
tags: [Masked Language Model, Transformer, BERT, Language Modeling, Model Architecture]
---
We seek to understand how the representations of individual tokens and the
structure of the learned feature space evolve between layers in deep neural
networks under different learning objectives. We focus on the Transformers for
our analysis as they have been shown effective on various tasks, including
machine translation (MT), standard left-to-right language models (LM) and
masked language modeling (MLM). Previous work used black-box probing tasks to
show that the representations learned by the Transformer differ significantly
depending on the objective. In this work, we use canonical correlation analysis
and mutual information estimators to study how information flows across
Transformer layers and how this process depends on the choice of learning
objective. For example, as you go from bottom to top layers, information about
the past in left-to-right language models gets vanished and predictions about
the future get formed. In contrast, for MLM, representations initially acquire
information about the context around the token, partially forgetting the token
identity and producing a more generalized token representation. The token
identity then gets recreated at the top MLM layers.