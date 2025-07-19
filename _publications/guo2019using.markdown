---
layout: publication
title: Using Database Rule For Weak Supervised Text-to-sql Generation
authors: Guo Tong, Gao Huilin
conference: Proceedings of the 24th ACM SIGKDD International Conference on Knowledge
  Discovery &amp; Data Mining
year: 2019
bibkey: guo2019using
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.00620'}]
tags: [RAG, Training Techniques, BERT, Model Architecture, Fine Tuning, KDD]
---
We present a simple way to do the task of text-to-SQL problem with weak
supervision. We call it Rule-SQL. Given the question and the answer from the
database table without the SQL logic form, Rule-SQL use the rules based on
table column names and question string for the SQL exploration first and then
use the explored SQL for supervised training. We design several rules for
reducing the exploration search space. For the deep model, we leverage BERT for
the representation layer and separate the model to SELECT, AGG and WHERE parts.
The experiment result on WikiSQL outperforms the strong baseline of full
supervision and is comparable to the start-of-the-art weak supervised mothods.