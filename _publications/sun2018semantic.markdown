---
layout: publication
title: Semantic Parsing With Syntax- And Table-aware SQL Generation
authors: Sun et al.
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: sun2018semantic
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.08338'}]
tags: [Datasets, ACL, RAG]
---
We present a generative model to map natural language questions into SQL
queries. Existing neural network based approaches typically generate a SQL
query word-by-word, however, a large portion of the generated results are
incorrect or not executable due to the mismatch between question words and
table contents. Our approach addresses this problem by considering the
structure of table and the syntax of SQL language. The quality of the generated
SQL query is significantly improved through (1) learning to replicate content
from column names, cells or SQL keywords; and (2) improving the generation of
WHERE clause by leveraging the column-cell relation. Experiments are conducted
on WikiSQL, a recently released dataset with the largest question-SQL pairs.
Our approach significantly improves the state-of-the-art execution accuracy
from 69.0% to 74.4%.