---
layout: publication
title: 'DCMN+: Dual Co-matching Network For Multi-choice Reading Comprehension'
authors: Zhang et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: zhang2019dcmn
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.11511'}]
tags: [Reinforcement Learning, AAAI, Datasets]
---
Multi-choice reading comprehension is a challenging task to select an answer
from a set of candidate options when given passage and question. Previous
approaches usually only calculate question-aware passage representation and
ignore passage-aware question representation when modeling the relationship
between passage and question, which obviously cannot take the best of
information between passage and question. In this work, we propose dual
co-matching network (DCMN) which models the relationship among passage,
question and answer options bidirectionally. Besides, inspired by how human
solve multi-choice questions, we integrate two reading strategies into our
model: (i) passage sentence selection that finds the most salient supporting
sentences to answer the question, (ii) answer option interaction that encodes
the comparison information between answer options. DCMN integrated with the two
strategies (DCMN+) obtains state-of-the-art results on five multi-choice
reading comprehension datasets which are from different domains: RACE,
SemEval-2018 Task 11, ROCStories, COIN, MCTest.