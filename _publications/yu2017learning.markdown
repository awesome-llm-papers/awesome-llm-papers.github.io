---
layout: publication
title: Learning To Skim Text
authors: Yu Adams Wei, Lee Hongrae, Le Quoc V.
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: yu2017learning
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.06877'}]
tags: [Model Architecture, Evaluation, ACL, Datasets, Reinforcement Learning]
---
Recurrent Neural Networks are showing much promise in many sub-areas of
natural language processing, ranging from document classification to machine
translation to automatic question answering. Despite their promise, many
recurrent models have to read the whole text word by word, making it slow to
handle long documents. For example, it is difficult to use a recurrent network
to read a book and answer questions about it. In this paper, we present an
approach of reading text while skipping irrelevant information if needed. The
underlying model is a recurrent network that learns how far to jump after
reading a few words of the input text. We employ a standard policy gradient
method to train the model to make discrete jumping decisions. In our benchmarks
on four different tasks, including number prediction, sentiment analysis, news
article classification and automatic Q\&A, our proposed model, a modified LSTM
with jumping, is up to 6 times faster than the standard sequential LSTM, while
maintaining the same or even better accuracy.