---
layout: publication
title: Explainable Topic-enhanced Argument Mining From Heterogeneous Sources
authors: Si et al.
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
bibkey: si2023explainable
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.12131'}]
tags: [Datasets, Evaluation, EMNLP]
---
Given a controversial target such as ``nuclear energy'', argument mining aims
to identify the argumentative text from heterogeneous sources. Current
approaches focus on exploring better ways of integrating the target-associated
semantic information with the argumentative text. Despite their empirical
successes, two issues remain unsolved: (i) a target is represented by a word or
a phrase, which is insufficient to cover a diverse set of target-related
subtopics; (ii) the sentence-level topic information within an argument, which
we believe is crucial for argument mining, is ignored. To tackle the above
issues, we propose a novel explainable topic-enhanced argument mining approach.
Specifically, with the use of the neural topic model and the language model,
the target information is augmented by explainable topic representations.
Moreover, the sentence-level topic information within the argument is captured
by minimizing the distance between its latent topic distribution and its
semantic representation through mutual learning. Experiments have been
conducted on the benchmark dataset in both the in-target setting and the
cross-target setting. Results demonstrate the superiority of the proposed model
against the state-of-the-art baselines.