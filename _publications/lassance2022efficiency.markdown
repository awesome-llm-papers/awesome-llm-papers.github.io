---
layout: publication
title: An Efficiency Study For SPLADE Models
authors: "Lassance Carlos, Clinchant St\xE9phane"
conference: Proceedings of the 45th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2022
bibkey: lassance2022efficiency
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.03834'}]
tags: [Training Techniques, Evaluation, Efficiency And Optimization, Reinforcement
    Learning, SIGIR, Datasets]
---
Latency and efficiency issues are often overlooked when evaluating IR models
based on Pretrained Language Models (PLMs) in reason of multiple hardware and
software testing scenarios. Nevertheless, efficiency is an important part of
such systems and should not be overlooked.
  In this paper, we focus on improving the efficiency of the SPLADE model since
it has achieved state-of-the-art zero-shot performance and competitive results
on TREC collections. SPLADE efficiency can be controlled via a regularization
factor, but solely controlling this regularization has been shown to not be
efficient enough. In order to reduce the latency gap between SPLADE and
traditional retrieval systems, we propose several techniques including L1
regularization for queries, a separation of document/query encoders, a
FLOPS-regularized middle-training, and the use of faster query encoders. Our
benchmark demonstrates that we can drastically improve the efficiency of these
models while increasing the performance metrics on in-domain data. To our
knowledge, \{we propose the first neural models that, under the same computing
constraints, \textit\{achieve similar latency (less than 4ms difference) as
traditional BM25\}, while having \textit\{similar performance (less than 10%
MRR@10 reduction)\} as the state-of-the-art single-stage neural rankers on
in-domain data\}.