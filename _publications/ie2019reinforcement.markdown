---
layout: publication
title: 'Reinforcement Learning For Slate-based Recommender Systems: A Tractable Decomposition
  And Practical Methodology'
authors: Ie et al.
conference: ACM Computing Surveys
year: 2019
bibkey: ie2019reinforcement
citations: 250
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.12767'}]
tags: [Survey Paper, RAG, Agentic, Reinforcement Learning]
---
Most practical recommender systems focus on estimating immediate user
engagement without considering the long-term effects of recommendations on user
behavior. Reinforcement learning (RL) methods offer the potential to optimize
recommendations for long-term user engagement. However, since users are often
presented with slates of multiple items - which may have interacting effects on
user choice - methods are required to deal with the combinatorics of the RL
action space. In this work, we address the challenge of making slate-based
recommendations to optimize long-term value using RL. Our contributions are
three-fold. (i) We develop SLATEQ, a decomposition of value-based
temporal-difference and Q-learning that renders RL tractable with slates. Under
mild assumptions on user choice behavior, we show that the long-term value
(LTV) of a slate can be decomposed into a tractable function of its component
item-wise LTVs. (ii) We outline a methodology that leverages existing myopic
learning-based recommenders to quickly develop a recommender that handles LTV.
(iii) We demonstrate our methods in simulation, and validate the scalability of
decomposed TD-learning using SLATEQ in live experiments on YouTube.