---
layout: publication
title: Neural End-to-end Learning For Computational Argumentation Mining
authors: Steffen Eger, Johannes Daxenberger, Iryna Gurevych
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: eger2017neural
citations: 168
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.06104'}]
tags: ["COLING", "EACL", "EMNLP", "LREC", "NAACL", "TACL"]
short_authors: Steffen Eger, Johannes Daxenberger, Iryna Gurevych
---
We investigate neural techniques for end-to-end computational argumentation
mining (AM). We frame AM both as a token-based dependency parsing and as a
token-based sequence tagging problem, including a multi-task learning setup.
Contrary to models that operate on the argument component level, we find that
framing AM as dependency parsing leads to subpar performance results. In
contrast, less complex (local) tagging models based on BiLSTMs perform robustly
across classification scenarios, being able to catch long-range dependencies
inherent to the AM problem. Moreover, we find that jointly learning 'natural'
subtasks, in a multi-task learning setup, improves performance.