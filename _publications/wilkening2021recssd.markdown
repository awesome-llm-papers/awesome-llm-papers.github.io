---
layout: publication
title: 'Recssd: Near Data Processing For Solid State Drive Based Recommendation Inference'
authors: Wilkening et al.
conference: Proceedings of the 26th ACM International Conference on Architectural
  Support for Programming Languages and Operating Systems
year: 2021
bibkey: wilkening2021recssd
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.00075'}]
tags: [RAG, Reinforcement Learning, Applications]
---
Neural personalized recommendation models are used across a wide variety of
datacenter applications including search, social media, and entertainment.
State-of-the-art models comprise large embedding tables that have billions of
parameters requiring large memory capacities. Unfortunately, large and fast
DRAM-based memories levy high infrastructure costs. Conventional SSD-based
storage solutions offer an order of magnitude larger capacity, but have worse
read latency and bandwidth, degrading inference performance. RecSSD is a near
data processing based SSD memory system customized for neural recommendation
inference that reduces end-to-end model inference latency by 2X compared to
using COTS SSDs across eight industry-representative models.