---
layout: publication
title: Summary Level Training Of Sentence Rewriting For Abstractive Summarization
authors: Sanghwan Bae, Taeuk Kim, Jihoon Kim, Sang-goo Lee
conference: Proceedings of the 2nd Workshop on New Frontiers in Summarization
year: 2019
bibkey: bae2019summary
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.08752'}]
tags: ["Training Techniques"]
short_authors: Bae et al.
---
As an attempt to combine extractive and abstractive summarization, Sentence
Rewriting models adopt the strategy of extracting salient sentences from a
document first and then paraphrasing the selected ones to generate a summary.
However, the existing models in this framework mostly rely on sentence-level
rewards or suboptimal labels, causing a mismatch between a training objective
and evaluation metric. In this paper, we present a novel training signal that
directly maximizes summary-level ROUGE scores through reinforcement learning.
In addition, we incorporate BERT into our model, making good use of its ability
on natural language understanding. In extensive experiments, we show that a
combination of our proposed model and training procedure obtains new
state-of-the-art performance on both CNN/Daily Mail and New York Times
datasets. We also demonstrate that it generalizes better on DUC-2002 test set.