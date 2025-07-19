---
layout: publication
title: Neural Autoregressive Collaborative Filtering For Implicit Feedback
authors: Zheng et al.
conference: Proceedings of the 1st Workshop on Deep Learning for Recommender Systems
year: 2016
bibkey: zheng2016neural
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.07674'}]
tags: [Language Modeling, Training Techniques, Datasets, GPT]
---
This paper proposes implicit CF-NADE, a neural autoregressive model for
collaborative filtering tasks using implicit feedback ( e.g. click, watch,
browse behaviors). We first convert a users implicit feedback into a like
vector and a confidence vector, and then model the probability of the like
vector, weighted by the confidence vector. The training objective of implicit
CF-NADE is to maximize a weighted negative log-likelihood. We test the
performance of implicit CF-NADE on a dataset collected from a popular digital
TV streaming service. More specifically, in the experiments, we describe how to
convert watch counts into implicit relative rating, and feed into implicit
CF-NADE. Then we compare the performance of implicit CF-NADE model with the
popular implicit matrix factorization approach. Experimental results show that
implicit CF-NADE significantly outperforms the baseline.