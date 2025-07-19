---
layout: publication
title: 'URL-BERT: Training Webpage Representations Via Social Media Engagements'
authors: Qamar et al.
conference: Proceedings of the 14th ACM international conference on Information and
  knowledge management
year: 2023
bibkey: qamar2023url
citations: 125
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.16303'}]
tags: [Training Techniques, Tools, Evaluation, BERT, Model Architecture, CIKM, Reinforcement
    Learning, Datasets]
---
Understanding and representing webpages is crucial to online social networks
where users may share and engage with URLs. Common language model (LM) encoders
such as BERT can be used to understand and represent the textual content of
webpages. However, these representations may not model thematic information of
web domains and URLs or accurately capture their appeal to social media users.
In this work, we introduce a new pre-training objective that can be used to
adapt LMs to understand URLs and webpages. Our proposed framework consists of
two steps: (1) scalable graph embeddings to learn shallow representations of
URLs based on user engagement on social media and (2) a contrastive objective
that aligns LM representations with the aforementioned graph-based
representation. We apply our framework to the multilingual version of BERT to
obtain the model URL-BERT. We experimentally demonstrate that our continued
pre-training approach improves webpage understanding on a variety of tasks and
Twitter internal and external benchmarks.