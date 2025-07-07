---
layout: publication
title: Meta Policy Learning For Cold-start Conversational Recommendation
authors: Zhendong Chu, Hongning Wang, Yun Xiao, Bo Long, Lingfei Wu
conference: Arxiv
year: 2022
citations: 22
bibkey: chu2022meta
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.11788'}]
tags: [Transformer, Fine-Tuning, Reinforcement Learning, Agentic, RecSys, Model Architecture]
---
Conversational recommender systems (CRS) explicitly solicit users'
preferences for improved recommendations on the fly. Most existing CRS
solutions count on a single policy trained by reinforcement learning for a
population of users. However, for users new to the system, such a global policy
becomes ineffective to satisfy them, i.e., the cold-start challenge. In this
paper, we study CRS policy learning for cold-start users via meta-reinforcement
learning. We propose to learn a meta policy and adapt it to new users with only
a few trials of conversational recommendations. To facilitate fast policy
adaptation, we design three synergetic components. Firstly, we design a
meta-exploration policy dedicated to identifying user preferences via a few
exploratory conversations, which accelerates personalized policy adaptation
from the meta policy. Secondly, we adapt the item recommendation module for
each user to maximize the recommendation quality based on the collected
conversation states during conversations. Thirdly, we propose a
Transformer-based state encoder as the backbone to connect the previous two
components. It provides comprehensive state representations by modeling
complicated relations between positive and negative feedback during the
conversation. Extensive experiments on three datasets demonstrate the advantage
of our solution in serving new users, compared with a rich set of
state-of-the-art CRS solutions.