---
layout: publication
title: Automatic Generation Of Natural Language Explanations
authors: Felipe Costa, Sixun Ouyang, Peter Dolog, Aonghus Lawlor
conference: Companion Proceedings of the 23rd International Conference on Intelligent
  User Interfaces
year: 2018
bibkey: costa2017automatic
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.01561'}]
tags: ["Datasets", "Evaluation", "Model Architecture"]
short_authors: Costa et al.
---
An important task for recommender system is to generate explanations
according to a user's preferences. Most of the current methods for explainable
recommendations use structured sentences to provide descriptions along with the
recommendations they produce. However, those methods have neglected the
review-oriented way of writing a text, even though it is known that these
reviews have a strong influence over user's decision.
  In this paper, we propose a method for the automatic generation of natural
language explanations, for predicting how a user would write about an item,
based on user ratings from different items' features. We design a
character-level recurrent neural network (RNN) model, which generates an item's
review explanations using long-short term memories (LSTM). The model generates
text reviews given a combination of the review and ratings score that express
opinions about different factors or aspects of an item. Our network is trained
on a sub-sample from the large real-world dataset BeerAdvocate. Our empirical
evaluation using natural language processing metrics shows the generated text's
quality is close to a real user written review, identifying negation,
misspellings, and domain specific vocabulary.