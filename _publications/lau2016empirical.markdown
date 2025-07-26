---
layout: publication
title: An Empirical Evaluation Of Doc2vec With Practical Insights Into Document Embedding
  Generation
authors: Jey Han Lau, Timothy Baldwin
conference: Proceedings of the 1st Workshop on Representation Learning for NLP
year: 2016
bibkey: lau2016empirical
citations: 560
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1607.05368'}]
tags: ["Applications", "Evaluation"]
short_authors: Jey Han Lau, Timothy Baldwin
---
Recently, Le and Mikolov (2014) proposed doc2vec as an extension to word2vec
(Mikolov et al., 2013a) to learn document-level embeddings. Despite promising
results in the original paper, others have struggled to reproduce those
results. This paper presents a rigorous empirical evaluation of doc2vec over
two tasks. We compare doc2vec to two baselines and two state-of-the-art
document embedding methodologies. We found that doc2vec performs robustly when
using models trained on large external corpora, and can be further improved by
using pre-trained word embeddings. We also provide recommendations on
hyper-parameter settings for general purpose applications, and release source
code to induce document embeddings using our trained doc2vec models.