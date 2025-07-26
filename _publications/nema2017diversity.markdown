---
layout: publication
title: Diversity Driven Attention Model For Query-based Abstractive Summarization
authors: Preksha Nema, Mitesh Khapra, Anirban Laha, Balaraman Ravindran
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: nema2017diversity
citations: 171
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.08300'}]
tags: ["Datasets"]
short_authors: Nema et al.
---
Abstractive summarization aims to generate a shorter version of the document
covering all the salient points in a compact and coherent fashion. On the other
hand, query-based summarization highlights those points that are relevant in
the context of a given query. The encode-attend-decode paradigm has achieved
notable success in machine translation, extractive summarization, dialog
systems, etc. But it suffers from the drawback of generation of repeated
phrases. In this work we propose a model for the query-based summarization task
based on the encode-attend-decode paradigm with two key additions (i) a query
attention model (in addition to document attention model) which learns to focus
on different portions of the query at different time steps (instead of using a
static representation for the query) and (ii) a new diversity based attention
model which aims to alleviate the problem of repeating phrases in the summary.
In order to enable the testing of this model we introduce a new query-based
summarization dataset building on debatepedia. Our experiments show that with
these two additions the proposed model clearly outperforms vanilla
encode-attend-decode models with a gain of 28% (absolute) in ROUGE-L scores.