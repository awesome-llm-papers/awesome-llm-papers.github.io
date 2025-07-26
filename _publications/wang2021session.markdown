---
layout: publication
title: Session-based Recommendation With Hypergraph Attention Networks
authors: Jianling Wang, Kaize Ding, Ziwei Zhu, James Caverlee
conference: Proceedings of the 2021 SIAM International Conference on Data Mining (SDM)
year: 2021
bibkey: wang2021session
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.14266'}]
tags: ["Datasets", "Evaluation"]
short_authors: Wang et al.
---
Session-based recommender systems aim to improve recommendations in
short-term sessions that can be found across many platforms. A critical
challenge is to accurately model user intent with only limited evidence in
these short sessions. For example, is a flower bouquet being viewed meant as
part of a wedding purchase or for home decoration? Such different perspectives
greatly impact what should be recommended next. Hence, this paper proposes a
novel session-based recommendation system empowered by hypergraph attention
networks. Three unique properties of the proposed approach are: (i) it
constructs a hypergraph for each session to model the item correlations defined
by various contextual windows in the session simultaneously, to uncover item
meanings; (ii) it is equipped with hypergraph attention layers to generate item
embeddings by flexibly aggregating the contextual information from correlated
items in the session; and (iii) it aggregates the dynamic item representations
for each session to infer the general purpose and current need, which is
decoded to infer the next interesting item in the session. Through experiments
on three benchmark datasets, we find the proposed model is effective in
generating informative dynamic item embeddings and providing more accurate
recommendations compared to the state-of-the-art.