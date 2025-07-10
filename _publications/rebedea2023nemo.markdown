---
layout: publication
title: 'Nemo Guardrails: A Toolkit For Controllable And Safe LLM Applications With
  Programmable Rails'
authors: Traian Rebedea, Razvan Dinu, Makesh Sreedhar, Christopher Parisien, Jonathan
  Cohen
conference: 'Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing: System Demonstrations'
year: 2023
citations: 34
bibkey: rebedea2023nemo
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.10501'}]
tags: [Reinforcement Learning, Training Techniques, Applications]
---
NeMo Guardrails is an open-source toolkit for easily adding programmable
guardrails to LLM-based conversational systems. Guardrails (or rails for short)
are a specific way of controlling the output of an LLM, such as not talking
about topics considered harmful, following a predefined dialogue path, using a
particular language style, and more. There are several mechanisms that allow
LLM providers and developers to add guardrails that are embedded into a
specific model at training, e.g. using model alignment. Differently, using a
runtime inspired from dialogue management, NeMo Guardrails allows developers to
add programmable rails to LLM applications - these are user-defined,
independent of the underlying LLM, and interpretable. Our initial results show
that the proposed approach can be used with several LLM providers to develop
controllable and safe LLM applications using programmable rails.