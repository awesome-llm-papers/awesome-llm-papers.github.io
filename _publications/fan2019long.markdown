---
layout: publication
title: 'ELI5: Long Form Question Answering'
authors: Angela Fan et al.
conference: Arxiv
year: 2019
citations: 104
bibkey: fan2019long
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.09190'}]
tags: [Language Modeling, Reinforcement Learning]
---
We introduce the first large-scale corpus for long-form question answering, a
task requiring elaborate and in-depth answers to open-ended questions. The
dataset comprises 270K threads from the Reddit forum ``Explain Like I'm Five''
(ELI5) where an online community provides answers to questions which are
comprehensible by five year olds. Compared to existing datasets, ELI5 comprises
diverse questions requiring multi-sentence answers. We provide a large set of
web documents to help answer the question. Automatic and human evaluations show
that an abstractive model trained with a multi-task objective outperforms
conventional Seq2Seq, language modeling, as well as a strong extractive
baseline. However, our best model is still far from human performance since
raters prefer gold responses in over 86% of cases, leaving ample opportunity
for future improvement.