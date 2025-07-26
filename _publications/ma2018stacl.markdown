---
layout: publication
title: 'STACL: Simultaneous Translation With Implicit Anticipation And Controllable
  Latency Using Prefix-to-prefix Framework'
authors: Mingbo Ma, Liang Huang, Hao Xiong, Renjie Zheng, Kaibo Liu, Baigong Zheng,
  Chuanqiang Zhang, Zhongjun He, Hairong Liu, Xing Li, Hua Wu, Haifeng Wang
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: ma2018stacl
citations: 190
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.08398'}]
tags: ["Tools"]
short_authors: Ma et al.
---
Simultaneous translation, which translates sentences before they are
finished, is useful in many scenarios but is notoriously difficult due to
word-order differences. While the conventional seq-to-seq framework is only
suitable for full-sentence translation, we propose a novel prefix-to-prefix
framework for simultaneous translation that implicitly learns to anticipate in
a single translation model. Within this framework, we present a very simple yet
surprisingly effective wait-k policy trained to generate the target sentence
concurrently with the source sentence, but always k words behind. Experiments
show our strategy achieves low latency and reasonable quality (compared to
full-sentence translation) on 4 directions: zh<->en and de<->en.