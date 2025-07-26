---
layout: publication
title: Personalizing A Dialogue System With Transfer Reinforcement Learning
authors: Kaixiang Mo, Shuangyin Li, Yu Zhang, Jiajun Li, Qiang Yang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: mo2016personalizing
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1610.02891'}]
tags: ["AAAI", "Reinforcement Learning"]
short_authors: Mo et al.
---
It is difficult to train a personalized task-oriented dialogue system because
the data collected from each individual is often insufficient. Personalized
dialogue systems trained on a small dataset can overfit and make it difficult
to adapt to different user needs. One way to solve this problem is to consider
a collection of multiple users' data as a source domain and an individual
user's data as a target domain, and to perform a transfer learning from the
source to the target domain. By following this idea, we propose
"PETAL"(PErsonalized Task-oriented diALogue), a transfer-learning framework
based on POMDP to learn a personalized dialogue system. The system first learns
common dialogue knowledge from the source domain and then adapts this knowledge
to the target user. This framework can avoid the negative transfer problem by
considering differences between source and target users. The policy in the
personalized POMDP can learn to choose different actions appropriately for
different users. Experimental results on a real-world coffee-shopping data and
simulation data show that our personalized dialogue system can choose different
optimal actions for different users, and thus effectively improve the dialogue
quality under the personalized setting.