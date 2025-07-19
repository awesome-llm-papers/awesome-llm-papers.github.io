---
layout: publication
title: End-to-end Cross-domain Text-to-sql Semantic Parsing With Auxiliary Task
authors: Shi et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2021
bibkey: shi2021end
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.09588'}]
tags: [Tools, ACL, EMNLP, Applications, RAG, Reinforcement Learning]
---
In this work, we focus on two crucial components in the cross-domain
text-to-SQL semantic parsing task: schema linking and value filling. To
encourage the model to learn better encoding ability, we propose a column
selection auxiliary task to empower the encoder with the relevance matching
capability by using explicit learning targets. Furthermore, we propose two
value filling methods to build the bridge from the existing zero-shot semantic
parsers to real-world applications, considering most of the existing parsers
ignore the values filling in the synthesized SQL. With experiments on Spider,
our proposed framework improves over the baselines on the execution accuracy
and exact set match accuracy when database contents are unavailable, and
detailed analysis sheds light on future work.