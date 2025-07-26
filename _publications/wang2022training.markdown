---
layout: publication
title: 'Training Data Is More Valuable Than You Think: A Simple And Effective Method
  By Retrieving From Training Data'
authors: Shuohang Wang, Yichong Xu, Yuwei Fang, Yang Liu, Siqi Sun, Ruochen Xu, Chenguang
  Zhu, Michael Zeng
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: wang2022training
citations: 66
additional_links: [{name: Code, url: 'https://github.com/microsoft/REINA'}, {name: Paper,
    url: 'https://arxiv.org/abs/2203.08773'}]
tags: ["Training Techniques"]
short_authors: Wang et al.
---
Retrieval-based methods have been shown to be effective in NLP tasks via
introducing external knowledge. However, the indexing and retrieving of
large-scale corpora bring considerable computational cost. Surprisingly, we
found that REtrieving from the traINing datA (REINA) only can lead to
significant gains on multiple NLG and NLU tasks. We retrieve the labeled
training instances most similar to the input text and then concatenate them
with the input to feed into the model to generate the output. Experimental
results show that this simple method can achieve significantly better
performance on a variety of NLU and NLG tasks, including summarization, machine
translation, language modeling, and question answering tasks. For instance, our
proposed method achieved state-of-the-art results on XSum, BigPatent, and
CommonsenseQA. Our code is released, https://github.com/microsoft/REINA .