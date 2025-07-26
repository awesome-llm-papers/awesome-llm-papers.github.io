---
layout: publication
title: 'Infini-gram: Scaling Unbounded N-gram Language Models To A Trillion Tokens'
authors: Jiacheng Liu, Sewon Min, Luke Zettlemoyer, Yejin Choi, Hannaneh Hajishirzi
conference: No Venue
year: 2024
bibkey: liu2024infini
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.17377'}]
tags: ["Tools"]
short_authors: Liu et al.
---
Are n-gram language models still relevant in this era of neural large language models (LLMs)? Our answer is yes, and we show their values in both text analysis and improving neural LLMs. Yet this necessitates modernizing n-gram models in two aspects. First, we train them at the same data scale as neural LLMs -- 1.4 trillion tokens. This is the largest n-gram model ever built. Second, existing n-gram models use small n which hinders their performance; we instead allow n to be arbitrarily large, by introducing a new infty-gram LM with backoff. Instead of pre-computing n-gram count tables (which would be very expensive), we develop an engine named infini-gram -- powered by suffix arrays -- that can compute infty-gram (as well as n-gram with arbitrary n) probabilities with millisecond-level latency. The infty-gram framework and infini-gram engine enable us to conduct many novel and interesting analyses of human-written and machine-generated text: we find that the infty-gram LM has fairly high accuracy for next-token prediction (47%), and can complement neural LLMs to greatly reduce their language modeling perplexities. When analyzing machine-generated text, we also observe irregularities in the machine--infty-gram agreement level with respect to the suffix length, which indicates deficiencies in neural LLM pretraining and the positional embeddings of Transformers. We open-source our infini-gram engine in the hopes of enabling more study on how to best use verbatim information retrieved from large text corpora.

https://huggingface.co/discussions/paper/65baf35e87b68ba54f65c4e0