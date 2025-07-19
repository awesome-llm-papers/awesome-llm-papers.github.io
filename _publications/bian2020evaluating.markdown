---
layout: publication
title: Evaluating Semantic Interaction On Word Embeddings Via Simulation
authors: Bian Yali, Dowling Michelle, North Chris
conference: 'Proceedings of the 52nd Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2020
bibkey: bian2020evaluating
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.15824'}]
tags: [ACL, Evaluation]
---
Semantic interaction (SI) attempts to learn the user's cognitive intents as
they directly manipulate data projections during sensemaking activity. For text
analysis, prior implementations of SI have used common data features, such as
bag-of-words representations, for machine learning from user interactions.
Instead, we hypothesize that features derived from deep learning word
embeddings will enable SI to better capture the user's subtle intents. However,
evaluating these effects is difficult. SI systems are usually evaluated by a
human-centred qualitative approach, by observing the utility and effectiveness
of the application for end-users. This approach has drawbacks in terms of
replicability, scalability, and objectiveness, which makes it hard to perform
convincing contrast experiments between different SI models. To tackle this
problem, we explore a quantitative algorithm-centered analysis as a
complementary evaluation approach, by simulating users' interactions and
calculating the accuracy of the learned model. We use these methods to compare
word-embeddings to bag-of-words features for SI.