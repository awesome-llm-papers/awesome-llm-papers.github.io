---
layout: publication
title: A Comprehensive Exploration On Wikisql With Table-aware Word Contextualization
authors: Wonseok Hwang, Jinyeong Yim, Seunghyun Park, Minjoon Seo
conference: Arxiv
year: 2019
bibkey: hwang2019comprehensive
citations: 119
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.01069'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Hwang et al.
---
We present SQLova, the first Natural-language-to-SQL (NL2SQL) model to
achieve human performance in WikiSQL dataset. We revisit and discuss diverse
popular methods in NL2SQL literature, take a full advantage of BERT \{Devlin et
al., 2018) through an effective table contextualization method, and coherently
combine them, outperforming the previous state of the art by 8.2% and 2.5% in
logical form and execution accuracy, respectively. We particularly note that
BERT with a seq2seq decoder leads to a poor performance in the task, indicating
the importance of a careful design when using such large pretrained models. We
also provide a comprehensive analysis on the dataset and our model, which can
be helpful for designing future NL2SQL datsets and models. We especially show
that our model's performance is near the upper bound in WikiSQL, where we
observe that a large portion of the evaluation errors are due to wrong
annotations, and our model is already exceeding human performance by 1.3% in
execution accuracy.