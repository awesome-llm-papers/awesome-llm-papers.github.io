---
layout: publication
title: 'Agentrec: Agent Recommendation Using Sentence Embeddings Aligned To Human
  Feedback'
authors: Park Joshua, Zhang Yongfeng
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2025
bibkey: park2025agentrec
citations: 4978
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.13333'}]
tags: [Training Techniques, EMNLP, Prompting, Agentic, Evaluation, BERT, Model Architecture,
  Reinforcement Learning, Fine Tuning, Datasets]
---
Multi-agent systems must decide which agent is the most appropriate for a
given task. We propose a novel architecture for recommending which LLM agent
out of many should perform a task given a natural language prompt by extending
the Sentence-BERT (SBERT) encoder model. On test data, we are able to achieve a
top-1 accuracy of 92.2% with each classification taking less than 300
milliseconds. In contrast to traditional classification methods, our
architecture is computationally cheap, adaptive to new classes, interpretable,
and controllable with arbitrary metrics through reinforcement learning. By
encoding natural language prompts into sentence embeddings, our model captures
the semantic content relevant to recommending an agent. The distance between
sentence embeddings that belong to the same agent is then minimized through
fine-tuning and aligned to human values through reinforcement learning from
human feedback. This allows the classification of natural language prompts
based on their nearest neighbors by measuring the cosine similarity between
embeddings. This work is made possible through the generation of a synthetic
dataset for agent recommendation, which we have open-sourced to the public
along with the code for AgentRec recommendation system at
https://github.com/joshprk/agentrec.