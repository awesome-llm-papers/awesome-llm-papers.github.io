---
layout: publication
title: Deep Reinforcement Learning For List-wise Recommendations
authors: Xiangyu Zhao, Liang Zhang, Long Xia, Zhuoye Ding, Dawei Yin, Jiliang Tang
conference: Arxiv
year: 2018
bibkey: zhao2017deep
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.00209'}]
tags: ["Reinforcement Learning"]
short_authors: Zhao et al.
---
Recommender systems play a crucial role in mitigating the problem of
information overload by suggesting users' personalized items or services. The
vast majority of traditional recommender systems consider the recommendation
procedure as a static process and make recommendations following a fixed
strategy. In this paper, we propose a novel recommender system with the
capability of continuously improving its strategies during the interactions
with users. We model the sequential interactions between users and a
recommender system as a Markov Decision Process (MDP) and leverage
Reinforcement Learning (RL) to automatically learn the optimal strategies via
recommending trial-and-error items and receiving reinforcements of these items
from users' feedbacks. In particular, we introduce an online user-agent
interacting environment simulator, which can pre-train and evaluate model
parameters offline before applying the model online. Moreover, we validate the
importance of list-wise recommendations during the interactions between users
and agent, and develop a novel approach to incorporate them into the proposed
framework LIRD for list-wide recommendations. The experimental results based on
a real-world e-commerce dataset demonstrate the effectiveness of the proposed
framework.