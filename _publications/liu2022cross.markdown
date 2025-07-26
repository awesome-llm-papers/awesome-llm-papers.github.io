---
layout: publication
title: Cross-modal Causal Relational Reasoning For Event-level Visual Question Answering
authors: Yang Liu, Guanbin Li, Liang Lin
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2023
bibkey: liu2022cross
citations: 272
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.12647'}]
tags: ["Model Architecture"]
short_authors: Yang Liu, Guanbin Li, Liang Lin
---
Existing visual question answering methods often suffer from cross-modal
spurious correlations and oversimplified event-level reasoning processes that
fail to capture event temporality, causality, and dynamics spanning over the
video. In this work, to address the task of event-level visual question
answering, we propose a framework for cross-modal causal relational reasoning.
In particular, a set of causal intervention operations is introduced to
discover the underlying causal structures across visual and linguistic
modalities. Our framework, named Cross-Modal Causal RelatIonal Reasoning
(CMCIR), involves three modules: i) Causality-aware Visual-Linguistic Reasoning
(CVLR) module for collaboratively disentangling the visual and linguistic
spurious correlations via front-door and back-door causal interventions; ii)
Spatial-Temporal Transformer (STT) module for capturing the fine-grained
interactions between visual and linguistic semantics; iii) Visual-Linguistic
Feature Fusion (VLFF) module for learning the global semantic-aware
visual-linguistic representations adaptively. Extensive experiments on four
event-level datasets demonstrate the superiority of our CMCIR in discovering
visual-linguistic causal structures and achieving robust event-level visual
question answering. The datasets, code, and models are available at
https://github.com/HCPLab-SYSU/CMCIR.