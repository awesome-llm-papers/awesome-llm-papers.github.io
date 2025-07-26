---
layout: publication
title: Soft Contextual Data Augmentation For Neural Machine Translation
authors: Jinhua Zhu, Fei Gao, Lijun Wu, Yingce Xia, Tao Qin, Wengang Zhou, Xueqi Cheng,
  Tie-yan Liu
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: zhu2019soft
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.10523'}]
tags: ["Datasets"]
short_authors: Zhu et al.
---
While data augmentation is an important trick to boost the accuracy of deep
learning methods in computer vision tasks, its study in natural language tasks
is still very limited. In this paper, we present a novel data augmentation
method for neural machine translation. Different from previous augmentation
methods that randomly drop, swap or replace words with other words in a
sentence, we softly augment a randomly chosen word in a sentence by its
contextual mixture of multiple related words. More accurately, we replace the
one-hot representation of a word by a distribution (provided by a language
model) over the vocabulary, i.e., replacing the embedding of this word by a
weighted combination of multiple semantically similar words. Since the weights
of those words depend on the contextual information of the word to be replaced,
the newly generated sentences capture much richer information than previous
augmentation methods. Experimental results on both small scale and large scale
machine translation datasets demonstrate the superiority of our method over
strong baselines.