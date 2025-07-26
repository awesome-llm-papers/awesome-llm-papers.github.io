---
layout: publication
title: Does Syntax Need To Grow On Trees? Sources Of Hierarchical Inductive Bias In
  Sequence-to-sequence Networks
authors: R. Thomas Mccoy, Robert Frank, Tal Linzen
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: mccoy2020does
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.03632'}]
tags: ["Model Architecture", "TACL"]
short_authors: R. Thomas Mccoy, Robert Frank, Tal Linzen
---
Learners that are exposed to the same training data might generalize
differently due to differing inductive biases. In neural network models,
inductive biases could in theory arise from any aspect of the model
architecture. We investigate which architectural factors affect the
generalization behavior of neural sequence-to-sequence models trained on two
syntactic tasks, English question formation and English tense reinflection. For
both tasks, the training set is consistent with a generalization based on
hierarchical structure and a generalization based on linear order. All
architectural factors that we investigated qualitatively affected how models
generalized, including factors with no clear connection to hierarchical
structure. For example, LSTMs and GRUs displayed qualitatively different
inductive biases. However, the only factor that consistently contributed a
hierarchical bias across tasks was the use of a tree-structured model rather
than a model with sequential recurrence, suggesting that human-like syntactic
generalization requires architectural syntactic structure.