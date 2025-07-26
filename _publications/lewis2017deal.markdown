---
layout: publication
title: Deal Or No Deal? End-to-end Learning For Negotiation Dialogues
authors: Mike Lewis, Denis Yarats, Yann N. Dauphin, Devi Parikh, Dhruv Batra
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: lewis2017deal
citations: 332
additional_links: [{name: Code, url: 'https://github.com/facebookresearch/end-to-end-negotiator)'},
  {name: Paper, url: 'https://arxiv.org/abs/1706.05125'}]
tags: ["EMNLP"]
short_authors: Lewis et al.
---
Much of human dialogue occurs in semi-cooperative settings, where agents with
different goals attempt to agree on common decisions. Negotiations require
complex communication and reasoning skills, but success is easy to measure,
making this an interesting task for AI. We gather a large dataset of
human-human negotiations on a multi-issue bargaining task, where agents who
cannot observe each other's reward functions must reach an agreement (or a
deal) via natural language dialogue. For the first time, we show it is possible
to train end-to-end models for negotiation, which must learn both linguistic
and reasoning skills with no annotated dialogue states. We also introduce
dialogue rollouts, in which the model plans ahead by simulating possible
complete continuations of the conversation, and find that this technique
dramatically improves performance. Our code and dataset are publicly available
(https://github.com/facebookresearch/end-to-end-negotiator).