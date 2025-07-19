---
layout: publication
title: Deep Reinforcement Learning For Page-wise Recommendations
authors: Zhao et al.
conference: Proceedings of the 12th ACM Conference on Recommender Systems
year: 2018
bibkey: zhao2018deep
citations: 182
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.02343'}]
tags: [Tools, Agentic, Reinforcement Learning, Datasets, RecSys]
---
Recommender systems can mitigate the information overload problem by
suggesting users' personalized items. In real-world recommendations such as
e-commerce, a typical interaction between the system and its users is -- users
are recommended a page of items and provide feedback; and then the system
recommends a new page of items. To effectively capture such interaction for
recommendations, we need to solve two key problems -- (1) how to update
recommending strategy according to user's \textit\{real-time feedback\}, and 2)
how to generate a page of items with proper display, which pose tremendous
challenges to traditional recommender systems. In this paper, we study the
problem of page-wise recommendations aiming to address aforementioned two
challenges simultaneously. In particular, we propose a principled approach to
jointly generate a set of complementary items and the corresponding strategy to
display them in a 2-D page; and propose a novel page-wise recommendation
framework based on deep reinforcement learning, DeepPage, which can optimize a
page of items with proper display based on real-time feedback from users. The
experimental results based on a real-world e-commerce dataset demonstrate the
effectiveness of the proposed framework.