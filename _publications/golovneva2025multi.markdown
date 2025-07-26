---
layout: publication
title: Multi-token Attention
authors: Olga Golovneva, Tianlu Wang, Jason Weston, Sainbayar Sukhbaatar
conference: No Venue
year: 2025
bibkey: golovneva2025multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.00927'}]
tags: ["Memory & Context", "Model Architecture"]
short_authors: Golovneva et al.
---
Soft attention is a critical mechanism powering LLMs to locate relevant parts within a given context. However, individual attention weights are determined by the similarity of only a single query and key token vector. This "single token attention" bottlenecks the amount of information used in distinguishing a relevant part from the rest of the context. To address this issue, we propose a new attention method, Multi-Token Attention (MTA), which allows LLMs to condition their attention weights on multiple query and key vectors simultaneously. This is achieved by applying convolution operations over queries, keys and heads, allowing nearby queries and keys to affect each other's attention weights for more precise attention. As a result, our method can locate relevant context using richer, more nuanced information that can exceed a single vector's capacity. Through extensive evaluations, we demonstrate that MTA achieves enhanced performance on a range of popular benchmarks. Notably, it outperforms Transformer baseline models on standard language modeling tasks, and on tasks that require searching for information within long contexts, where our method's ability to leverage richer information proves particularly beneficial.

https://huggingface.co/discussions/paper/67ecc23c6a2bc6abdc2e91c2