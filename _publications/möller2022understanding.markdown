---
layout: publication
title: Understanding The Relation Of User And News Representations In Content-based
  Neural News Recommendation
authors: "M\xF6ller Lucas, Pad\xF3 Sebastian"
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2022
bibkey: "m\xF6ller2022understanding"
citations: 201
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.14704'}]
tags: [Datasets, Reinforcement Learning, ACL]
---
A number of models for neural content-based news recommendation have been
proposed. However, there is limited understanding of the relative importances
of the three main components of such systems (news encoder, user encoder, and
scoring function) and the trade-offs involved. In this paper, we assess the
hypothesis that the most widely used means of matching user and candidate news
representations is not expressive enough. We allow our system to model more
complex relations between the two by assessing more expressive scoring
functions. Across a wide range of baseline and established systems this results
in consistent improvements of around 6 points in AUC. Our results also indicate
a trade-off between the complexity of news encoder and scoring function: A
fairly simple baseline model scores well above 68% AUC on the MIND dataset and
comes within 2 points of the published state-of-the-art, while requiring a
fraction of the computational costs.