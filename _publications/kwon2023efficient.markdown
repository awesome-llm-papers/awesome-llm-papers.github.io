---
layout: publication
title: Efficient Memory Management For Large Language Model Serving With Pagedattention
authors: Woosuk Kwon, Zhuohan Li, Siyuan Zhuang, Ying Sheng, Lianmin Zheng, Cody Hao
  Yu, Joseph E. Gonzalez, Hao Zhang, Ion Stoica
conference: Proceedings of the 29th Symposium on Operating Systems Principles
year: 2023
bibkey: kwon2023efficient
citations: 259
additional_links: [{name: Code, url: 'https://github.com/vllm-project/vllm'}, {name: Paper,
    url: 'https://arxiv.org/abs/2309.06180'}]
tags: ["Memory & Context"]
short_authors: Kwon et al.
---
High throughput serving of large language models (LLMs) requires batching
sufficiently many requests at a time. However, existing systems struggle
because the key-value cache (KV cache) memory for each request is huge and
grows and shrinks dynamically. When managed inefficiently, this memory can be
significantly wasted by fragmentation and redundant duplication, limiting the
batch size. To address this problem, we propose PagedAttention, an attention
algorithm inspired by the classical virtual memory and paging techniques in
operating systems. On top of it, we build vLLM, an LLM serving system that
achieves (1) near-zero waste in KV cache memory and (2) flexible sharing of KV
cache within and across requests to further reduce memory usage. Our
evaluations show that vLLM improves the throughput of popular LLMs by
2-4\\(\times\\) with the same level of latency compared to the state-of-the-art
systems, such as FasterTransformer and Orca. The improvement is more pronounced
with longer sequences, larger models, and more complex decoding algorithms.
vLLM's source code is publicly available at
https://github.com/vllm-project/vllm