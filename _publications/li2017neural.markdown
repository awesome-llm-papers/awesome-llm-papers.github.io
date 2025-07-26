---
layout: publication
title: Neural Attentive Session-based Recommendation
authors: Jing Li, Pengjie Ren, Zhumin Chen, Zhaochun Ren, Jun Ma
conference: Proceedings of the 40th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2017
bibkey: li2017neural
citations: 285
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.04725'}]
tags: ["Model Architecture", "SIGIR"]
short_authors: Li et al.
---
Given e-commerce scenarios that user profiles are invisible, session-based
recommendation is proposed to generate recommendation results from short
sessions. Previous work only considers the user's sequential behavior in the
current session, whereas the user's main purpose in the current session is not
emphasized. In this paper, we propose a novel neural networks framework, i.e.,
Neural Attentive Recommendation Machine (NARM), to tackle this problem.
Specifically, we explore a hybrid encoder with an attention mechanism to model
the user's sequential behavior and capture the user's main purpose in the
current session, which are combined as a unified session representation later.
We then compute the recommendation scores for each candidate item with a
bi-linear matching scheme based on this unified session representation. We
train NARM by jointly learning the item and session representations as well as
their matchings. We carried out extensive experiments on two benchmark
datasets. Our experimental results show that NARM outperforms state-of-the-art
baselines on both datasets. Furthermore, we also find that NARM achieves a
significant improvement on long sessions, which demonstrates its advantages in
modeling the user's sequential behavior and main purpose simultaneously.