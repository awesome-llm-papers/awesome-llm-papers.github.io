---
layout: publication
title: Cognitive Graph For Multi-hop Reading Comprehension At Scale
authors: Ming Ding, Chang Zhou, Qibin Chen, Hongxia Yang, Jie Tang
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: ding2019cognitive
citations: 204
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.05460'}]
tags: ["Model Architecture"]
short_authors: Ding et al.
---
We propose a new CogQA framework for multi-hop question answering in
web-scale documents. Inspired by the dual process theory in cognitive science,
the framework gradually builds a \textit\{cognitive graph\} in an iterative
process by coordinating an implicit extraction module (System 1) and an
explicit reasoning module (System 2). While giving accurate answers, our
framework further provides explainable reasoning paths. Specifically, our
implementation based on BERT and graph neural network efficiently handles
millions of documents for multi-hop reasoning questions in the HotpotQA
fullwiki dataset, achieving a winning joint \\(F_1\\) score of 34.9 on the
leaderboard, compared to 23.6 of the best competitor.