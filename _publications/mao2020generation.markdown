---
layout: publication
title: Generation-augmented Retrieval For Open-domain Question Answering
authors: Yuning Mao, Pengcheng He, Xiaodong Liu, Yelong Shen, Jianfeng Gao, Jiawei
  Han, Weizhu Chen
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: mao2020generation
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.08553'}]
tags: ["Datasets", "Language Modeling"]
short_authors: Mao et al.
---
We propose Generation-Augmented Retrieval (GAR) for answering open-domain
questions, which augments a query through text generation of heuristically
discovered relevant contexts without external resources as supervision. We
demonstrate that the generated contexts substantially enrich the semantics of
the queries and GAR with sparse representations (BM25) achieves comparable or
better performance than state-of-the-art dense retrieval methods such as DPR.
We show that generating diverse contexts for a query is beneficial as fusing
their results consistently yields better retrieval accuracy. Moreover, as
sparse and dense representations are often complementary, GAR can be easily
combined with DPR to achieve even better performance. GAR achieves
state-of-the-art performance on Natural Questions and TriviaQA datasets under
the extractive QA setup when equipped with an extractive reader, and
consistently outperforms other retrieval methods when the same generative
reader is used.