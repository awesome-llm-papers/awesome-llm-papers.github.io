---
layout: publication
title: Incorporating User Micro-behaviors And Item Knowledge Into Multi-task Learning
  For Session-based Recommendation
authors: Meng Wenjing, Yang Deqing, Xiao Yanghua
conference: Proceedings of the 43rd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2020
bibkey: meng2020incorporating
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.06922'}]
tags: [Alt, Tools, Evaluation, SIGIR, Datasets]
---
Session-based recommendation (SR) has become an important and popular
component of various e-commerce platforms, which aims to predict the next
interacted item based on a given session. Most of existing SR models only focus
on exploiting the consecutive items in a session interacted by a certain user,
to capture the transition pattern among the items. Although some of them have
been proven effective, the following two insights are often neglected. First, a
user's micro-behaviors, such as the manner in which the user locates an item,
the activities that the user commits on an item (e.g., reading comments, adding
to cart), offer fine-grained and deep understanding of the user's preference.
Second, the item attributes, also known as item knowledge, provide side
information to model the transition pattern among interacted items and
alleviate the data sparsity problem. These insights motivate us to propose a
novel SR model MKM-SR in this paper, which incorporates user Micro-behaviors
and item Knowledge into Multi-task learning for Session-based Recommendation.
Specifically, a given session is modeled on micro-behavior level in MKM-SR,
i.e., with a sequence of item-operation pairs rather than a sequence of items,
to capture the transition pattern in the session sufficiently. Furthermore, we
propose a multi-task learning paradigm to involve learning knowledge embeddings
which plays a role as an auxiliary task to promote the major task of SR. It
enables our model to obtain better session representations, resulting in more
precise SR recommendation results. The extensive evaluations on two benchmark
datasets demonstrate MKM-SR's superiority over the state-of-the-art SR models,
justifying the strategy of incorporating knowledge learning.