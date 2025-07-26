---
layout: publication
title: Towards End-to-end Reinforcement Learning Of Dialogue Agents For Information
  Access
authors: Bhuwan Dhingra, Lihong Li, Xiujun Li, Jianfeng Gao, Yun-nung Chen, Faisal
  Ahmed, Li Deng
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: dhingra2016towards
citations: 315
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.00777'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Dhingra et al.
---
This paper proposes KB-InfoBot -- a multi-turn dialogue agent which helps
users search Knowledge Bases (KBs) without composing complicated queries. Such
goal-oriented dialogue agents typically need to interact with an external
database to access real-world knowledge. Previous systems achieved this by
issuing a symbolic query to the KB to retrieve entries based on their
attributes. However, such symbolic operations break the differentiability of
the system and prevent end-to-end training of neural dialogue agents. In this
paper, we address this limitation by replacing symbolic queries with an induced
"soft" posterior distribution over the KB that indicates which entities the
user is interested in. Integrating the soft retrieval process with a
reinforcement learner leads to higher task success rate and reward in both
simulations and against real users. We also present a fully neural end-to-end
agent, trained entirely from user feedback, and discuss its application towards
personalized dialogue agents. The source code is available at
https://github.com/MiuLab/KB-InfoBot.