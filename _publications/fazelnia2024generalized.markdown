---
layout: publication
title: Generalized User Representations For Transfer Learning
authors: Fazelnia et al.
conference: Proceedings of the Fifteenth ACM International Conference on Web Search
  and Data Mining
year: 2024
bibkey: fazelnia2024generalized
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.00584'}]
tags: [RAG, Alt, Tools, Evaluation, Fine Tuning]
---
We present a novel framework for user representation in large-scale
recommender systems, aiming at effectively representing diverse user taste in a
generalized manner. Our approach employs a two-stage methodology combining
representation learning and transfer learning. The representation learning
model uses an autoencoder that compresses various user features into a
representation space. In the second stage, downstream task-specific models
leverage user representations via transfer learning instead of curating user
features individually. We further augment this methodology on the
representation's input features to increase flexibility and enable reaction to
user events, including new user experiences, in Near-Real Time. Additionally,
we propose a novel solution to manage deployment of this framework in
production models, allowing downstream models to work independently. We
validate the performance of our framework through rigorous offline and online
experiments within a large-scale system, showcasing its remarkable efficacy
across multiple evaluation tasks. Finally, we show how the proposed framework
can significantly reduce infrastructure costs compared to alternative
approaches.