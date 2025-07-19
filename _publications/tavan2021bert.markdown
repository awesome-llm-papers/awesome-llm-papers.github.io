---
layout: publication
title: 'BERT-DRE: BERT With Deep Recursive Encoder For Natural Language Sentence Matching'
authors: Tavan et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2021
bibkey: tavan2021bert
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.02188'}]
tags: [Model Architecture, BERT, Evaluation, ACL, RAG, Datasets, Attention Mechanism]
---
This paper presents a deep neural architecture, for Natural Language Sentence
Matching (NLSM) by adding a deep recursive encoder to BERT so called BERT with
Deep Recursive Encoder (BERT-DRE). Our analysis of model behavior shows that
BERT still does not capture the full complexity of text, so a deep recursive
encoder is applied on top of BERT. Three Bi-LSTM layers with residual
connection are used to design a recursive encoder and an attention module is
used on top of this encoder. To obtain the final vector, a pooling layer
consisting of average and maximum pooling is used. We experiment our model on
four benchmarks, SNLI, FarsTail, MultiNLI, SciTail, and a novel Persian
religious questions dataset. This paper focuses on improving the BERT results
in the NLSM task. In this regard, comparisons between BERT-DRE and BERT are
conducted, and it is shown that in all cases, BERT-DRE outperforms BERT. The
BERT algorithm on the religious dataset achieved an accuracy of 89.70%, and
BERT-DRE architectures improved to 90.29% using the same dataset.