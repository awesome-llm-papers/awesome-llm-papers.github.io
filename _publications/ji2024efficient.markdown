---
layout: publication
title: Efficient Document Ranking With Learnable Late Interactions
authors: Ji et al.
conference: ACM Transactions on Information Systems
year: 2024
bibkey: ji2024efficient
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.17968'}]
tags: [Model Architecture, RAG, BERT]
---
Cross-Encoder (CE) and Dual-Encoder (DE) models are two fundamental
approaches for query-document relevance in information retrieval. To predict
relevance, CE models use joint query-document embeddings, while DE models
maintain factorized query and document embeddings; usually, the former has
higher quality while the latter benefits from lower latency. Recently,
late-interaction models have been proposed to realize more favorable
latency-quality tradeoffs, by using a DE structure followed by a lightweight
scorer based on query and document token embeddings. However, these lightweight
scorers are often hand-crafted, and there is no understanding of their
approximation power; further, such scorers require access to individual
document token embeddings, which imposes an increased latency and storage
burden. In this paper, we propose novel learnable late-interaction models
(LITE) that resolve these issues. Theoretically, we prove that LITE is a
universal approximator of continuous scoring functions, even for relatively
small embedding dimension. Empirically, LITE outperforms previous
late-interaction models such as ColBERT on both in-domain and zero-shot
re-ranking tasks. For instance, experiments on MS MARCO passage re-ranking show
that LITE not only yields a model with better generalization, but also lowers
latency and requires 0.25x storage compared to ColBERT.