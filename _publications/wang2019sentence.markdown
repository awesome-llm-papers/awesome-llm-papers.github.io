---
layout: publication
title: Sentence Embedding Alignment For Lifelong Relation Extraction
authors: Hong Wang, Wenhan Xiong, Mo Yu, Xiaoxiao Guo, Shiyu Chang, William Yang Wang
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: wang2019sentence
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.02588'}]
tags: ["Applications", "Training Techniques"]
short_authors: Wang et al.
---
Conventional approaches to relation extraction usually require a fixed set of
pre-defined relations. Such requirement is hard to meet in many real
applications, especially when new data and relations are emerging incessantly
and it is computationally expensive to store all data and re-train the whole
model every time new data and relations come in. We formulate such a
challenging problem as lifelong relation extraction and investigate
memory-efficient incremental learning methods without catastrophically
forgetting knowledge learned from previous tasks. We first investigate a
modified version of the stochastic gradient methods with a replay memory, which
surprisingly outperforms recent state-of-the-art lifelong learning methods. We
further propose to improve this approach to alleviate the forgetting problem by
anchoring the sentence embedding space. Specifically, we utilize an explicit
alignment model to mitigate the sentence embedding distortion of the learned
model when training on new data and new relations. Experiment results on
multiple benchmarks show that our proposed method significantly outperforms the
state-of-the-art lifelong learning approaches.