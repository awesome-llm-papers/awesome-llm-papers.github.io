---
layout: publication
title: 'Compressed Chain Of Thought: Efficient Reasoning Through Dense Representations'
authors: Jeffrey Cheng, Benjamin van Durme
conference: No Venue
year: 2024
bibkey: cheng2024compressed
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6762f21fa3eed649f9889a49'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.13171'}]
tags: ["Prompting", "Tools"]
short_authors: Jeffrey Cheng, Benjamin van Durme
---
Chain-of-thought (CoT) decoding enables language models to improve reasoning performance at the cost of high generation latency in decoding. Recent proposals have explored variants of contemplation tokens, a term we introduce that refers to special tokens used during inference to allow for extra computation. Prior work has considered fixed-length sequences drawn from a discrete set of embeddings as contemplation tokens. Here we propose Compressed Chain-of-Thought (CCoT), a framework to generate contentful and continuous contemplation tokens of variable sequence length. The generated contemplation tokens are compressed representations of explicit reasoning chains, and our method can be applied to off-the-shelf decoder language models. Through experiments, we illustrate how CCoT enables additional reasoning over dense contentful representations to achieve corresponding improvements in accuracy. Moreover, the reasoning improvements can be adaptively modified on demand by controlling the number of contemplation tokens generated.

https://huggingface.co/discussions/paper/6762f21fa3eed649f9889a49