---
layout: publication
title: 'Many Hands Make Light Work: Task-oriented Dialogue System With Module-based
  Mixture-of-experts'
authors: Su Ruolin, Juang Biing-hwang
conference: Journal of Experimental Botany
year: 2024
bibkey: su2024many
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.09744'}]
tags: [RAG, Evaluation, Datasets, Efficiency And Optimization]
---
Task-oriented dialogue systems are broadly used in virtual assistants and
other automated services, providing interfaces between users and machines to
facilitate specific tasks. Nowadays, task-oriented dialogue systems have
greatly benefited from pre-trained language models (PLMs). However, their
task-solving performance is constrained by the inherent capacities of PLMs, and
scaling these models is expensive and complex as the model size becomes larger.
To address these challenges, we propose Soft Mixture-of-Expert Task-Oriented
Dialogue system (SMETOD) which leverages an ensemble of Mixture-of-Experts
(MoEs) to excel at subproblems and generate specialized outputs for
task-oriented dialogues. SMETOD also scales up a task-oriented dialogue system
with simplicity and flexibility while maintaining inference efficiency. We
extensively evaluate our model on three benchmark functionalities: intent
prediction, dialogue state tracking, and dialogue response generation.
Experimental results demonstrate that SMETOD achieves state-of-the-art
performance on most evaluated metrics. Moreover, comparisons against existing
strong baselines show that SMETOD has a great advantage in the cost of
inference and correctness in problem-solving.