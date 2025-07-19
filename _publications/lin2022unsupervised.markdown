---
layout: publication
title: Unsupervised Cross-task Generalization Via Retrieval Augmentation
authors: Lin et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: lin2022unsupervised
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.07937'}]
tags: [ACL]
---
Humans can perform unseen tasks by recalling relevant skills acquired
previously and then generalizing them to the target tasks, even if there is no
supervision at all. In this paper, we aim to improve this kind of cross-task
generalization ability of massive multi-task language models, such as T0 and
FLAN, in an unsupervised setting. We propose a retrieval-augmentation method
named ReCross that takes a few unlabelled examples as queries to retrieve a
small subset of upstream data and uses them to update the multi-task model for
better generalization. ReCross is a straightforward yet effective retrieval
method that combines both efficient dense retrieval and effective pair-wise
reranking. Our results and analysis show that it significantly outperforms both
non-retrieval methods and other baseline methods.