---
layout: publication
title: 'Estimation-action-reflection: Towards Deep Interaction Between Conversational
  And Recommender Systems'
authors: Wenqiang Lei, Xiangnan He, Yisong Miao, Qingyun Wu, Richang Hong, Min-yen
  Kan, Tat-seng Chua
conference: Proceedings of the 13th International Conference on Web Search and Data
  Mining
year: 2020
bibkey: lei2020estimation
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.09102'}]
tags: ["Datasets", "Tools"]
short_authors: Lei et al.
---
Recommender systems are embracing conversational technologies to obtain user
preferences dynamically, and to overcome inherent limitations of their static
models. A successful Conversational Recommender System (CRS) requires proper
handling of interactions between conversation and recommendation. We argue that
three fundamental problems need to be solved: 1) what questions to ask
regarding item attributes, 2) when to recommend items, and 3) how to adapt to
the users' online feedback. To the best of our knowledge, there lacks a unified
framework that addresses these problems.
  In this work, we fill this missing interaction framework gap by proposing a
new CRS framework named Estimation-Action-Reflection, or EAR, which consists of
three stages to better converse with users. (1) Estimation, which builds
predictive models to estimate user preference on both items and item
attributes; (2) Action, which learns a dialogue policy to determine whether to
ask attributes or recommend items, based on Estimation stage and conversation
history; and (3) Reflection, which updates the recommender model when a user
rejects the recommendations made by the Action stage. We present two
conversation scenarios on binary and enumerated questions, and conduct
extensive experiments on two datasets from Yelp and LastFM, for each scenario,
respectively. Our experiments demonstrate significant improvements over the
state-of-the-art method CRM [32], corresponding to fewer conversation turns and
a higher level of recommendation hits.