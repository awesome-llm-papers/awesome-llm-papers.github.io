---
layout: publication
title: Stronger Baselines For Retrieval-augmented Generation With Long-context Language
  Models
authors: Laitenberger Alex, Manning Christopher D., Liu Nelson F.
conference: Transactions of the Association for Computational Linguistics
year: 2025
bibkey: laitenberger2025stronger
citations: 130
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.03989'}]
tags: [Merging, Evaluation, TACL, Agentic, ACL, RAG, Datasets]
---
With the rise of long-context language models (LMs) capable of processing tens of thousands of tokens in a single pass, do multi-stage retrieval-augmented generation (RAG) pipelines still offer measurable benefits over simpler, single-stage approaches? To assess this question, we conduct a controlled evaluation for QA tasks under systematically scaled token budgets, comparing two recent multi-stage pipelines, ReadAgent and RAPTOR, against three baselines, including DOS RAG (Document's Original Structure RAG), a simple retrieve-then-read method that preserves original passage order. Despite its straightforward design, DOS RAG consistently matches or outperforms more intricate methods on multiple long-context QA benchmarks. We recommend establishing DOS RAG as a simple yet strong baseline for future RAG evaluations, pairing it with emerging embedding and language models to assess trade-offs between complexity and effectiveness as model capabilities evolve.