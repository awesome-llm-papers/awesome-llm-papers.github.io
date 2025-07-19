---
layout: publication
title: 'Recxplainer: Amortized Attribute-based Personalized Explanations For Recommender
  Systems'
authors: Verma et al.
conference: Proceedings of the 24th International Conference on Intelligent User Interfaces
year: 2022
bibkey: verma2022recxplainer
citations: 113
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.14935'}]
tags: [Interpretability And Explainability, Tools, Evaluation, Reinforcement Learning,
  Datasets]
---
Recommender systems influence many of our interactions in the digital world
-- impacting how we shop for clothes, sorting what we see when browsing YouTube
or TikTok, and determining which restaurants and hotels we are shown when using
hospitality platforms. Modern recommender systems are large, opaque models
trained on a mixture of proprietary and open-source datasets. Naturally, issues
of trust arise on both the developer and user side: is the system working
correctly, and why did a user receive (or not receive) a particular
recommendation? Providing an explanation alongside a recommendation alleviates
some of these concerns. The status quo for auxiliary recommender system
feedback is either user-specific explanations (e.g., "users who bought item B
also bought item A") or item-specific explanations (e.g., "we are recommending
item A because you watched/bought item B"). However, users bring personalized
context into their search experience, valuing an item as a function of that
item's attributes and their own personal preferences. In this work, we propose
RecXplainer, a novel method for generating fine-grained explanations based on a
user's preferences over the attributes of recommended items. We evaluate
RecXplainer on five real-world and large-scale recommendation datasets using
five different kinds of recommender systems to demonstrate the efficacy of
RecXplainer in capturing users' preferences over item attributes and using them
to explain recommendations. We also compare RecXplainer to five baselines and
show RecXplainer's exceptional performance on ten metrics.