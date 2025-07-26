---
layout: publication
title: 'Program Induction By Rationale Generation : Learning To Solve And Explain
  Algebraic Word Problems'
authors: Wang Ling, Dani Yogatama, Chris Dyer, Phil Blunsom
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: ling2017program
citations: 261
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.04146'}]
tags: ["Datasets"]
short_authors: Ling et al.
---
Solving algebraic word problems requires executing a series of arithmetic
operations---a program---to obtain a final answer. However, since programs can
be arbitrarily complicated, inducing them directly from question-answer pairs
is a formidable challenge. To make this task more feasible, we solve these
problems by generating answer rationales, sequences of natural language and
human-readable mathematical expressions that derive the final answer through a
series of small steps. Although rationales do not explicitly specify programs,
they provide a scaffolding for their structure via intermediate milestones. To
evaluate our approach, we have created a new 100,000-sample dataset of
questions, answers and rationales. Experimental results show that indirect
supervision of program learning via answer rationales is a promising strategy
for inducing arithmetic programs.