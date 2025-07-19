---
layout: publication
title: 'Retentive Network: A Successor To Transformer For Large Language Models'
authors: Sun et al.
conference: Arxiv
year: 2023
bibkey: sun2023retentive
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.08621'}]
tags: [Training Techniques, Attention Mechanism, Transformer, Model Architecture,
  Time Series, Language Modeling, Reinforcement Learning]
---
In this work, we propose Retentive Network (RetNet) as a foundation
architecture for large language models, simultaneously achieving training
parallelism, low-cost inference, and good performance. We theoretically derive
the connection between recurrence and attention. Then we propose the retention
mechanism for sequence modeling, which supports three computation paradigms,
i.e., parallel, recurrent, and chunkwise recurrent. Specifically, the parallel
representation allows for training parallelism. The recurrent representation
enables low-cost \\(O(1)\\) inference, which improves decoding throughput, latency,
and GPU memory without sacrificing performance. The chunkwise recurrent
representation facilitates efficient long-sequence modeling with linear
complexity, where each chunk is encoded parallelly while recurrently
summarizing the chunks. Experimental results on language modeling show that
RetNet achieves favorable scaling results, parallel training, low-cost
deployment, and efficient inference. The intriguing properties make RetNet a
strong successor to Transformer for large language models. Code will be
available at https://aka.ms/retnet.