---
layout: publication
title: 'Turngpt: A Transformer-based Language Model For Predicting Turn-taking In
  Spoken Dialog'
authors: Erik Ekstedt, Gabriel Skantze
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
citations: 21
bibkey: ekstedt2020transformer
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.10874'}]
tags: [Model Architecture, Attention Mechanism, Transformer, RAG, GPT]
---
Syntactic and pragmatic completeness is known to be important for turn-taking
prediction, but so far machine learning models of turn-taking have used such
linguistic information in a limited way. In this paper, we introduce TurnGPT, a
transformer-based language model for predicting turn-shifts in spoken dialog.
The model has been trained and evaluated on a variety of written and spoken
dialog datasets. We show that the model outperforms two baselines used in prior
work. We also report on an ablation study, as well as attention and gradient
analyses, which show that the model is able to utilize the dialog context and
pragmatic completeness for turn-taking prediction. Finally, we explore the
model's potential in not only detecting, but also projecting, turn-completions.