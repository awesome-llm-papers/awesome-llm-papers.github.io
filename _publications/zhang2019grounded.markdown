---
layout: publication
title: Grounded Conversation Generation As Guided Traverses In Commonsense Knowledge
  Graphs
authors: Houyu Zhang, Zhenghao Liu, Chenyan Xiong, Zhiyuan Liu
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: zhang2019grounded
citations: 123
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.02707'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Zhang et al.
---
Human conversations naturally evolve around related concepts and scatter to
multi-hop concepts. This paper presents a new conversation generation model,
ConceptFlow, which leverages commonsense knowledge graphs to explicitly model
conversation flows. By grounding conversations to the concept space,
ConceptFlow represents the potential conversation flow as traverses in the
concept space along commonsense relations. The traverse is guided by graph
attentions in the concept graph, moving towards more meaningful directions in
the concept space, in order to generate more semantic and informative
responses. Experiments on Reddit conversations demonstrate ConceptFlow's
effectiveness over previous knowledge-aware conversation models and GPT-2 based
models while using 70% fewer parameters, confirming the advantage of explicit
modeling conversation structures. All source codes of this work are available
at https://github.com/thunlp/ConceptFlow.