---
layout: publication
title: 'MS MARCO: A Human Generated Machine Reading Comprehension Dataset'
authors: Payal Bajaj, Daniel Campos, Nick Craswell, Li Deng, Jianfeng Gao, Xiaodong
  Liu, Rangan Majumder, Andrew Mcnamara, Bhaskar Mitra, Tri Nguyen, Mir Rosenberg,
  Xia Song, Alina Stoica, Saurabh Tiwary, Tong Wang
conference: Arxiv
year: 2016
bibkey: bajaj2016ms
citations: 1353
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.09268'}]
tags: ["Datasets"]
short_authors: Bajaj et al.
---
We introduce a large scale MAchine Reading COmprehension dataset, which we
name MS MARCO. The dataset comprises of 1,010,916 anonymized
questions---sampled from Bing's search query logs---each with a human generated
answer and 182,669 completely human rewritten generated answers. In addition,
the dataset contains 8,841,823 passages---extracted from 3,563,535 web
documents retrieved by Bing---that provide the information necessary for
curating the natural language answers. A question in the MS MARCO dataset may
have multiple answers or no answers at all. Using this dataset, we propose
three different tasks with varying levels of difficulty: (i) predict if a
question is answerable given a set of context passages, and extract and
synthesize the answer as a human would (ii) generate a well-formed answer (if
possible) based on the context passages that can be understood with the
question and passage context, and finally (iii) rank a set of retrieved
passages given a question. The size of the dataset and the fact that the
questions are derived from real user search queries distinguishes MS MARCO from
other well-known publicly available datasets for machine reading comprehension
and question-answering. We believe that the scale and the real-world nature of
this dataset makes it attractive for benchmarking machine reading comprehension
and question-answering models.