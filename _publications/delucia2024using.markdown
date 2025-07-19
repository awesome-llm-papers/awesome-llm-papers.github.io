---
layout: publication
title: Using Natural Language Inference To Improve Persona Extraction From Dialogue
  In A New Domain
authors: Delucia et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2024
bibkey: delucia2024using
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.06742'}]
tags: [Training Techniques, ACL, Agentic, Datasets, Reinforcement Learning]
---
While valuable datasets such as PersonaChat provide a foundation for training
persona-grounded dialogue agents, they lack diversity in conversational and
narrative settings, primarily existing in the "real" world. To develop dialogue
agents with unique personas, models are trained to converse given a specific
persona, but hand-crafting these persona can be time-consuming, thus methods
exist to automatically extract persona information from existing
character-specific dialogue. However, these persona-extraction models are also
trained on datasets derived from PersonaChat and struggle to provide
high-quality persona information from conversational settings that do not take
place in the real world, such as the fantasy-focused dataset, LIGHT. Creating
new data to train models on a specific setting is human-intensive, thus
prohibitively expensive. To address both these issues, we introduce a natural
language inference method for post-hoc adapting a trained persona extraction
model to a new setting. We draw inspiration from the literature of dialog
natural language inference (NLI), and devise NLI-reranking methods to extract
structured persona information from dialogue. Compared to existing persona
extraction models, our method returns higher-quality extracted persona and
requires less human annotation.