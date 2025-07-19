---
layout: publication
title: Leveraging Large Language Models For Sequential Recommendation
authors: Harte et al.
conference: Proceedings of the 17th ACM Conference on Recommender Systems
year: 2023
bibkey: harte2023leveraging
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.09261'}]
tags: [Model Architecture, BERT, Applications, RAG, Datasets, RecSys, Attention Mechanism]
---
Sequential recommendation problems have received increasing attention in
research during the past few years, leading to the inception of a large variety
of algorithmic approaches. In this work, we explore how large language models
(LLMs), which are nowadays introducing disruptive effects in many AI-based
applications, can be used to build or improve sequential recommendation
approaches. Specifically, we devise and evaluate three approaches to leverage
the power of LLMs in different ways. Our results from experiments on two
datasets show that initializing the state-of-the-art sequential recommendation
model BERT4Rec with embeddings obtained from an LLM improves NDCG by 15-20%
compared to the vanilla BERT4Rec model. Furthermore, we find that a simple
approach that leverages LLM embeddings for producing recommendations, can
provide competitive performance by highlighting semantically related items. We
publicly share the code and data of our experiments to ensure reproducibility.