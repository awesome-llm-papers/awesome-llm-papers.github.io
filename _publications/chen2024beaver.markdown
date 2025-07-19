---
layout: publication
title: 'BEAVER: An Enterprise Benchmark For Text-to-sql'
authors: Chen et al.
conference: Proceedings of the VLDB Endowment
year: 2024
bibkey: chen2024beaver
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.02038'}]
tags: [RAG, Prompting, Evaluation, Reinforcement Learning, Datasets]
---
Existing text-to-SQL benchmarks have largely been constructed from web tables
with human-generated question-SQL pairs. LLMs typically show strong results on
these benchmarks, leading to a belief that LLMs are effective at text-to-SQL
tasks. However, how these results transfer to enterprise settings is unclear
because tables in enterprise databases might differ substantially from web
tables in structure and content. To contend with this problem, we introduce a
new dataset BEAVER, the first enterprise text-to-SQL benchmark sourced from
real private enterprise data warehouses. This dataset includes natural language
queries and their correct SQL statements, which we collected from actual query
logs. We then benchmark off-the-shelf LLMs on this dataset. LLMs perform
poorly, even when augmented with standard prompt engineering and RAG
techniques. We identify three main reasons for the poor performance: (1)
schemas of enterprise tables are more complex than the schemas in public data,
resulting in SQL-generation tasks intrinsically harder; (2) business-oriented
questions are often more complex, requiring joins over multiple tables,
aggregations, and nested queries; (3) public LLMs cannot train on private
enterprise data warehouses that are not publicly accessible, and therefore it
is difficult for the model to learn to solve (1) and (2). We believe BEAVER
will facilitate future research in building text-to-SQL systems that perform
better in enterprise settings.