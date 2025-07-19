---
layout: publication
title: A Compositional Approach To Language Modeling
authors: Arora Kushal, Rangarajan Anand
conference: Lecture Notes in Computer Science
year: 2016
bibkey: arora2016compositional
citations: 168
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1604.00100'}]
tags: [Language Modeling, Reinforcement Learning, Evaluation]
---
Traditional language models treat language as a finite state automaton on a
probability space over words. This is a very strong assumption when modeling
something inherently complex such as language. In this paper, we challenge this
by showing how the linear chain assumption inherent in previous work can be
translated into a sequential composition tree. We then propose a new model that
marginalizes over all possible composition trees thereby removing any
underlying structural assumptions. As the partition function of this new model
is intractable, we use a recently proposed sentence level evaluation metric
Contrastive Entropy to evaluate our model. Given this new evaluation metric, we
report more than 100% improvement across distortion levels over current state
of the art recurrent neural network based language models.