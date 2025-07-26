---
layout: publication
title: 'Cosrec: 2D Convolutional Neural Networks For Sequential Recommendation'
authors: An Yan, Shuo Cheng, Wang-cheng Kang, Mengting Wan, Julian Mcauley
conference: Proceedings of the 28th ACM International Conference on Information and
  Knowledge Management
year: 2019
bibkey: yan2019cosrec
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.09972'}]
tags: ["CIKM"]
short_authors: Yan et al.
---
Sequential patterns play an important role in building modern recommender
systems. To this end, several recommender systems have been built on top of
Markov Chains and Recurrent Models (among others). Although these sequential
models have proven successful at a range of tasks, they still struggle to
uncover complex relationships nested in user purchase histories. In this paper,
we argue that modeling pairwise relationships directly leads to an efficient
representation of sequential features and captures complex item correlations.
Specifically, we propose a 2D convolutional network for sequential
recommendation (CosRec). It encodes a sequence of items into a three-way
tensor; learns local features using 2D convolutional filters; and aggregates
high-order interactions in a feedforward manner. Quantitative results on two
public datasets show that our method outperforms both conventional methods and
recent sequence-based approaches, achieving state-of-the-art performance on
various evaluation metrics.