---
layout: publication
title: Using Local Knowledge Graph Construction To Scale Seq2seq Models To Multi-document
  Inputs
authors: Angela Fan, Claire Gardent, Chloe Braud, Antoine Bordes
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: fan2019using
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.08435'}]
tags: ["EMNLP"]
short_authors: Fan et al.
---
Query-based open-domain NLP tasks require information synthesis from long and
diverse web results. Current approaches extractively select portions of web
text as input to Sequence-to-Sequence models using methods such as TF-IDF
ranking. We propose constructing a local graph structured knowledge base for
each query, which compresses the web search information and reduces redundancy.
We show that by linearizing the graph into a structured input sequence, models
can encode the graph representations within a standard Sequence-to-Sequence
setting. For two generative tasks with very long text input, long-form question
answering and multi-document summarization, feeding graph representations as
input can achieve better performance than using retrieved text portions.