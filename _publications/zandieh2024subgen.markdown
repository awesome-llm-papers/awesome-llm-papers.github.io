---
layout: publication
title: 'Subgen: Token Generation In Sublinear Time And Memory'
authors: Zandieh et al.
conference: SIAM Journal on Discrete Mathematics
year: 2024
bibkey: zandieh2024subgen
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.06082'}]
tags: [Model Architecture, Efficiency And Optimization, Evaluation, Attention Mechanism]
---
Despite the significant success of large language models (LLMs), their
extensive memory requirements pose challenges for deploying them in
long-context token generation. The substantial memory footprint of LLM decoders
arises from the necessity to store all previous tokens in the attention module,
a requirement imposed by key-value (KV) caching. In this work, our focus is on
developing an efficient compression technique for the KV cache. Empirical
evidence indicates a significant clustering tendency within key embeddings in
the attention module. Building on this key insight, we have devised a novel
caching method with sublinear complexity, employing online clustering on key
tokens and online \\(ℓ₂\\) sampling on values. The result is a provably
accurate and efficient attention decoding algorithm, termed SubGen. Not only
does this algorithm ensure a sublinear memory footprint and sublinear time
complexity, but we also establish a tight error bound for our approach.
Empirical evaluations on long-context question-answering tasks demonstrate that
SubGen significantly outperforms existing and state-of-the-art KV cache
compression methods in terms of performance and efficiency.