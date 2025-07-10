---
layout: publication
title: 'REPLUG: Retrieval-augmented Black-box Language Models'
authors: Weijia Shi et al.
conference: 'Proceedings of the 2024 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies (Volume 1:
  Long Papers)'
year: 2023
citations: 34
bibkey: shi2023retrieval
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2301.12652v4'}]
tags: [Language Modeling, Model Architecture, Attention Mechanism, Transformer, RAG,
  Tools, GPT]
---
We introduce REPLUG, a retrieval-augmented language modeling framework that
treats the language model (LM) as a black box and augments it with a tuneable
retrieval model. Unlike prior retrieval-augmented LMs that train language
models with special cross attention mechanisms to encode the retrieved text,
REPLUG simply prepends retrieved documents to the input for the frozen
black-box LM. This simple design can be easily applied to any existing
retrieval and language models. Furthermore, we show that the LM can be used to
supervise the retrieval model, which can then find documents that help the LM
make better predictions. Our experiments demonstrate that REPLUG with the tuned
retriever significantly improves the performance of GPT-3 (175B) on language
modeling by 6.3%, as well as the performance of Codex on five-shot MMLU by
5.1%.