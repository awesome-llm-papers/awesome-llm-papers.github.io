---
layout: publication
title: 'Model-based Interactive Semantic Parsing: A Unified Framework And A Text-to-sql
  Case Study'
authors: Yao et al.
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: yao2019model
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.05389'}]
tags: [EMNLP, Agentic, Tools, Reinforcement Learning, Datasets]
---
As a promising paradigm, interactive semantic parsing has shown to improve
both semantic parsing accuracy and user confidence in the results. In this
paper, we propose a new, unified formulation of the interactive semantic
parsing problem, where the goal is to design a model-based intelligent agent.
The agent maintains its own state as the current predicted semantic parse,
decides whether and where human intervention is needed, and generates a
clarification question in natural language. A key part of the agent is a world
model: it takes a percept (either an initial question or subsequent feedback
from the user) and transitions to a new state. We then propose a simple yet
remarkably effective instantiation of our framework, demonstrated on two
text-to-SQL datasets (WikiSQL and Spider) with different state-of-the-art base
semantic parsers. Compared to an existing interactive semantic parsing approach
that treats the base parser as a black box, our approach solicits less user
feedback but yields higher run-time accuracy.