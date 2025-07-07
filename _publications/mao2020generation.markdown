---
layout: publication
title: Generation-augmented Retrieval For Open-domain Question Answering
authors: Yuning Mao et al.
conference: Arxiv
year: 2020
citations: 46
bibkey: mao2020generation
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.08553'}]
tags: [Language Modeling]
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