---
layout: publication
title: The Effect Of Downstream Classification Tasks For Evaluating Sentence Embeddings
authors: Potash Peter
conference: 'Proceedings of the 2016 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2019
bibkey: potash2019effect
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.02228'}]
tags: [Datasets, ACL, NAACL]
---
One popular method for quantitatively evaluating the utility of sentence
embeddings involves using them in downstream language processing tasks that
require sentence representations as input. One simple such task is
classification, where the sentence representations are used to train and test
models on several classification datasets. We argue that by evaluating sentence
representations in such a manner, the goal of the representations becomes
learning a low-dimensional factorization of a sentence-task label matrix. We
show how characteristics of this matrix can affect the ability for a
low-dimensional factorization to perform as sentence representations in a suite
of classification tasks. Primarily, sentences that have more labels across all
possible classification tasks have a higher reconstruction loss, however the
general nature of this effect is ultimately dependent on the overall
distribution of labels across all possible sentences.