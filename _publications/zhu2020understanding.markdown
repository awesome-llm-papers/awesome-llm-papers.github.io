---
layout: publication
title: Understanding Learning Dynamics For Neural Machine Translation
authors: Zhu et al.
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2020
bibkey: zhu2020understanding
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.02199'}]
tags: [Datasets, ACL, Training Techniques, Evaluation]
---
Despite the great success of NMT, there still remains a severe challenge: it
is hard to interpret the internal dynamics during its training process. In this
paper we propose to understand learning dynamics of NMT by using a recent
proposed technique named Loss Change Allocation
(LCA)~\citep\{lan-2019-loss-change-allocation\}. As LCA requires calculating the
gradient on an entire dataset for each update, we instead present an
approximate to put it into practice in NMT scenario. %motivated by the lesson
from sgd. Our simulated experiment shows that such approximate calculation is
efficient and is empirically proved to deliver consistent results to the
brute-force implementation. In particular, extensive experiments on two
standard translation benchmark datasets reveal some valuable findings.