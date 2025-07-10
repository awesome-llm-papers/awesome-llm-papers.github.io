---
layout: publication
title: Robust Text-to-sql Generation With Execution-guided Decoding
authors: Chenglong Wang et al.
conference: Arxiv
year: 2018
citations: 67
bibkey: wang2018robust
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.03100'}]
tags: [GPT, RAG]
---
We consider the problem of neural semantic parsing, which translates natural
language questions into executable SQL queries. We introduce a new mechanism,
execution guidance, to leverage the semantics of SQL. It detects and excludes
faulty programs during the decoding procedure by conditioning on the execution
of partially generated program. The mechanism can be used with any
autoregressive generative model, which we demonstrate on four state-of-the-art
recurrent or template-based semantic parsing models. We demonstrate that
execution guidance universally improves model performance on various
text-to-SQL datasets with different scales and query complexity: WikiSQL, ATIS,
and GeoQuery. As a result, we achieve new state-of-the-art execution accuracy
of 83.8% on WikiSQL.