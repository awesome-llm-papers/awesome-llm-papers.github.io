---
layout: publication
title: Learning Multi-granularity User Intent Unit For Session-based Recommendation
authors: Guo et al.
conference: Proceedings of the Fifteenth ACM International Conference on Web Search
  and Data Mining
year: 2021
bibkey: guo2021learning
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.13197'}]
tags: [RAG, Datasets, Merging]
---
Session-based recommendation aims to predict a user's next action based on
previous actions in the current session. The major challenge is to capture
authentic and complete user preferences in the entire session. Recent work
utilizes graph structure to represent the entire session and adopts Graph
Neural Network to encode session information. This modeling choice has been
proved to be effective and achieved remarkable results. However, most of the
existing studies only consider each item within the session independently and
do not capture session semantics from a high-level perspective. Such limitation
often leads to severe information loss and increases the difficulty of
capturing long-range dependencies within a session. Intuitively, compared with
individual items, a session snippet, i.e., a group of locally consecutive
items, is able to provide supplemental user intents which are hardly captured
by existing methods. In this work, we propose to learn multi-granularity
consecutive user intent unit to improve the recommendation performance.
Specifically, we creatively propose Multi-granularity Intent Heterogeneous
Session Graph which captures the interactions between different granularity
intent units and relieves the burden of long-dependency. Moreover, we propose
the Intent Fusion Ranking module to compose the recommendation results from
various granularity user intents. Compared with current methods that only
leverage intents from individual items, IFR benefits from different granularity
user intents to generate more accurate and comprehensive session
representation, thus eventually boosting recommendation performance. We conduct
extensive experiments on five session-based recommendation datasets and the
results demonstrate the effectiveness of our method.