---
layout: publication
title: Probing What Different NLP Tasks Teach Machines About Function Word Comprehension
authors: Najoung Kim, Roma Patel, Adam Poliak, Alex Wang, Patrick Xia, R. Thomas Mccoy,
  Ian Tenney, Alexis Ross, Tal Linzen, Benjamin van Durme, Samuel R. Bowman, Ellie
  Pavlick
conference: Proceedings of the Eighth Joint Conference on Lexical and Computational
  Semantics (*SEM 2019)
year: 2019
bibkey: kim2019probing
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.11544'}]
tags: ["Datasets"]
short_authors: Kim et al.
---
We introduce a set of nine challenge tasks that test for the understanding of
function words. These tasks are created by structurally mutating sentences from
existing datasets to target the comprehension of specific types of function
words (e.g., prepositions, wh-words). Using these probing tasks, we explore the
effects of various pretraining objectives for sentence encoders (e.g., language
modeling, CCG supertagging and natural language inference (NLI)) on the learned
representations. Our results show that pretraining on language modeling
performs the best on average across our probing tasks, supporting its
widespread use for pretraining state-of-the-art NLP models, and CCG
supertagging and NLI pretraining perform comparably. Overall, no pretraining
objective dominates across the board, and our function word probing tasks
highlight several intuitive differences between pretraining objectives, e.g.,
that NLI helps the comprehension of negation.