---
layout: publication
title: 'Recshard: Statistical Feature-based Memory Optimization For Industry-scale
  Neural Recommendation'
authors: Sethi et al.
conference: Proceedings of the 27th ACM International Conference on Architectural
  Support for Programming Languages and Operating Systems
year: 2022
bibkey: sethi2022recshard
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.10095'}]
tags: [RAG, Reinforcement Learning, Training Techniques, Efficiency And Optimization]
---
We propose RecShard, a fine-grained embedding table (EMB) partitioning and
placement technique for deep learning recommendation models (DLRMs). RecShard
is designed based on two key observations. First, not all EMBs are equal, nor
all rows within an EMB are equal in terms of access patterns. EMBs exhibit
distinct memory characteristics, providing performance optimization
opportunities for intelligent EMB partitioning and placement across a tiered
memory hierarchy. Second, in modern DLRMs, EMBs function as hash tables. As a
result, EMBs display interesting phenomena, such as the birthday paradox,
leaving EMBs severely under-utilized. RecShard determines an optimal EMB
sharding strategy for a set of EMBs based on training data distributions and
model characteristics, along with the bandwidth characteristics of the
underlying tiered memory hierarchy. In doing so, RecShard achieves over 6 times
higher EMB training throughput on average for capacity constrained DLRMs. The
throughput increase comes from improved EMB load balance by over 12 times and
from the reduced access to the slower memory by over 87 times.