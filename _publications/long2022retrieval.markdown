---
layout: publication
title: Retrieval Oriented Masking Pre-training Language Model For Dense Passage Retrieval
authors: Long et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: long2022retrieval
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.15133'}]
tags: [Masked Language Model, Model Architecture, Training Techniques, BERT, Evaluation,
  ACL, Datasets, Language Modeling, Alt]
---
Pre-trained language model (PTM) has been shown to yield powerful text
representations for dense passage retrieval task. The Masked Language Modeling
(MLM) is a major sub-task of the pre-training process. However, we found that
the conventional random masking strategy tend to select a large number of
tokens that have limited effect on the passage retrieval task (e,g. stop-words
and punctuation). By noticing the term importance weight can provide valuable
information for passage retrieval, we hereby propose alternative retrieval
oriented masking (dubbed as ROM) strategy where more important tokens will have
a higher probability of being masked out, to capture this straightforward yet
essential information to facilitate the language model pre-training process.
Notably, the proposed new token masking method will not change the architecture
and learning objective of original PTM. Our experiments verify that the
proposed ROM enables term importance information to help language model
pre-training thus achieving better performance on multiple passage retrieval
benchmarks.