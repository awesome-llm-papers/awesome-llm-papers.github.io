---
layout: publication
title: Sql-to-text Generation With Graph-to-sequence Model
authors: Kun Xu, Lingfei Wu, Zhiguo Wang, Yansong Feng, Vadim Sheinin
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: xu2018sql
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.05255'}]
tags: ["EMNLP"]
short_authors: Xu et al.
---
Previous work approaches the SQL-to-text generation task using vanilla
Seq2Seq models, which may not fully capture the inherent graph-structured
information in SQL query. In this paper, we first introduce a strategy to
represent the SQL query as a directed graph and then employ a graph-to-sequence
model to encode the global structure information into node embeddings. This
model can effectively learn the correlation between the SQL query pattern and
its interpretation. Experimental results on the WikiSQL dataset and
Stackoverflow dataset show that our model significantly outperforms the Seq2Seq
and Tree2Seq baselines, achieving the state-of-the-art performance.