---
layout: publication
title: Attentive Knowledge-aware Graph Convolutional Networks With Collaborative Guidance
  For Personalized Recommendation
authors: Chen et al.
conference: 2022 IEEE 38th International Conference on Data Engineering (ICDE)
year: 2021
bibkey: chen2021attentive
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.02046'}]
tags: [Attention Mechanism, RSS, Model Architecture, Reinforcement Learning, Datasets]
---
To alleviate data sparsity and cold-start problems of traditional recommender
systems (RSs), incorporating knowledge graphs (KGs) to supplement auxiliary
information has attracted considerable attention recently. However, simply
integrating KGs in current KG-based RS models is not necessarily a guarantee to
improve the recommendation performance, which may even weaken the holistic
model capability. This is because the construction of these KGs is independent
of the collection of historical user-item interactions; hence, information in
these KGs may not always be helpful for recommendation to all users.
  In this paper, we propose attentive Knowledge-aware Graph convolutional
networks with Collaborative Guidance for personalized Recommendation (CG-KGR).
CG-KGR is a novel knowledge-aware recommendation model that enables ample and
coherent learning of KGs and user-item interactions, via our proposed
Collaborative Guidance Mechanism. Specifically, CG-KGR first encapsulates
historical interactions to interactive information summarization. Then CG-KGR
utilizes it as guidance to extract information out of KGs, which eventually
provides more precise personalized recommendation. We conduct extensive
experiments on four real-world datasets over two recommendation tasks, i.e.,
Top-K recommendation and Click-Through rate (CTR) prediction. The experimental
results show that the CG-KGR model significantly outperforms recent
state-of-the-art models by 1.4-27.0% in terms of Recall metric on Top-K
recommendation.