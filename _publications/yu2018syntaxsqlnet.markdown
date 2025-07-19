---
layout: publication
title: 'Syntaxsqlnet: Syntax Tree Networks For Complex And Cross-domaintext-to-sql
  Task'
authors: Yu et al.
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: yu2018syntaxsqlnet
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.05237'}]
tags: [Training Techniques, Attention Mechanism, EMNLP, Evaluation, Model Architecture]
---
Most existing studies in text-to-SQL tasks do not require generating complex
SQL queries with multiple clauses or sub-queries, and generalizing to new,
unseen databases. In this paper we propose SyntaxSQLNet, a syntax tree network
to address the complex and cross-domain text-to-SQL generation task.
SyntaxSQLNet employs a SQL specific syntax tree-based decoder with SQL
generation path history and table-aware column attention encoders. We evaluate
SyntaxSQLNet on the Spider text-to-SQL task, which contains databases with
multiple tables and complex SQL queries with multiple SQL clauses and nested
queries. We use a database split setting where databases in the test set are
unseen during training. Experimental results show that SyntaxSQLNet can handle
a significantly greater number of complex SQL examples than prior work,
outperforming the previous state-of-the-art model by 7.3% in exact matching
accuracy. We also show that SyntaxSQLNet can further improve the performance by
an additional 7.5% using a cross-domain augmentation method, resulting in a
14.8% improvement in total. To our knowledge, we are the first to study this
complex and cross-domain text-to-SQL task.