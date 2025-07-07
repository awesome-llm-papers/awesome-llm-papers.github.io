---
layout: publication
title: Generating Empathetic Responses By Looking Ahead The User's Sentiment
authors: Jamin Shin, Peng Xu, Andrea Madotto, Pascale Fung
conference: Arxiv
year: 2019
citations: 21
bibkey: shin2019generating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.08487'}]
tags: [Tools, Agentic, Reinforcement Learning]
---
An important aspect of human conversation difficult for machines is
conversing with empathy, which is to understand the user's emotion and respond
appropriately. Recent neural conversation models that attempted to generate
empathetic responses either focused on conditioning the output to a given
emotion, or incorporating the current user emotional state. However, these
approaches do not factor in how the user would feel towards the generated
response. Hence, in this paper, we propose Sentiment Look-ahead, which is a
novel perspective for empathy that models the future user emotional state. In
short, Sentiment Look-ahead is a reward function under a reinforcement learning
framework that provides a higher reward to the generative model when the
generated utterance improves the user's sentiment. We implement and evaluate
three different possible implementations of sentiment look-ahead and
empirically show that our proposed approach can generate significantly more
empathetic, relevant, and fluent responses than other competitive baselines
such as multitask learning.