---
layout: publication
title: Understanding The Behaviors Of BERT In Ranking
authors: Yifan Qiao, Chenyan Xiong, Zhenghao Liu, Zhiyuan Liu
conference: Arxiv
year: 2019
bibkey: qiao2019understanding
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.07531'}]
tags: ["Model Architecture"]
short_authors: Qiao et al.
---
This paper studies the performances and behaviors of BERT in ranking tasks.
We explore several different ways to leverage the pre-trained BERT and
fine-tune it on two ranking tasks: MS MARCO passage reranking and TREC Web
Track ad hoc document ranking. Experimental results on MS MARCO demonstrate the
strong effectiveness of BERT in question-answering focused passage ranking
tasks, as well as the fact that BERT is a strong interaction-based seq2seq
matching model. Experimental results on TREC show the gaps between the BERT
pre-trained on surrounding contexts and the needs of ad hoc document ranking.
Analyses illustrate how BERT allocates its attentions between query-document
tokens in its Transformer layers, how it prefers semantic matches between
paraphrase tokens, and how that differs with the soft match patterns learned by
a click-trained neural ranker.