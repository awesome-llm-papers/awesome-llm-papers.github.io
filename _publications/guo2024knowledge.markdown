---
layout: publication
title: Knowledge Graph Enhanced Language Agents For Recommendation
authors: Guo et al.
conference: Expert Systems with Applications
year: 2024
bibkey: guo2024knowledge
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.19627'}]
tags: [RAG, Agentic, Tools, Evaluation, Reinforcement Learning, Applications, Datasets]
---
Language agents have recently been used to simulate human behavior and
user-item interactions for recommendation systems. However, current language
agent simulations do not understand the relationships between users and items,
leading to inaccurate user profiles and ineffective recommendations. In this
work, we explore the utility of Knowledge Graphs (KGs), which contain extensive
and reliable relationships between users and items, for recommendation. Our key
insight is that the paths in a KG can capture complex relationships between
users and items, eliciting the underlying reasons for user preferences and
enriching user profiles. Leveraging this insight, we propose Knowledge Graph
Enhanced Language Agents(KGLA), a framework that unifies language agents and KG
for recommendation systems. In the simulated recommendation scenario, we
position the user and item within the KG and integrate KG paths as natural
language descriptions into the simulation. This allows language agents to
interact with each other and discover sufficient rationale behind their
interactions, making the simulation more accurate and aligned with real-world
cases, thus improving recommendation performance. Our experimental results show
that KGLA significantly improves recommendation performance (with a 33%-95%
boost in NDCG@1 among three widely used benchmarks) compared to the previous
best baseline method.