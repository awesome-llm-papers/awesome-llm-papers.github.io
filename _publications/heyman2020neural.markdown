---
layout: publication
title: 'Neural Code Search Revisited: Enhancing Code Snippet Retrieval Through Natural
  Language Intent'
authors: Heyman Geert, van Cutsem Tom
conference: Proceedings of the 2nd ACM SIGPLAN International Workshop on Machine Learning
  and Programming Languages
year: 2020
bibkey: heyman2020neural
citations: 119
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.12193'}]
tags: [Fine Tuning, RAG, Evaluation, Datasets]
---
In this work, we propose and study annotated code search: the retrieval of
code snippets paired with brief descriptions of their intent using natural
language queries. On three benchmark datasets, we investigate how code
retrieval systems can be improved by leveraging descriptions to better capture
the intents of code snippets. Building on recent progress in transfer learning
and natural language processing, we create a domain-specific retrieval model
for code annotated with a natural language description. We find that our model
yields significantly more relevant search results (with absolute gains up to
20.6% in mean reciprocal rank) compared to state-of-the-art code retrieval
methods that do not use descriptions but attempt to compute the intent of
snippets solely from unannotated code.