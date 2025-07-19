---
layout: publication
title: Don't Give Me The Details, Just The Summary! Topic-aware Convolutional Neural
  Networks For Extreme Summarization
authors: Narayan Shashi, Cohen Shay B., Lapata Mirella
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: narayan2018don
citations: 334
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.08745'}]
tags: [EMNLP, Model Architecture, Reinforcement Learning, Datasets]
---
We introduce extreme summarization, a new single-document summarization task
which does not favor extractive strategies and calls for an abstractive
modeling approach. The idea is to create a short, one-sentence news summary
answering the question "What is the article about?". We collect a real-world,
large-scale dataset for this task by harvesting online articles from the
British Broadcasting Corporation (BBC). We propose a novel abstractive model
which is conditioned on the article's topics and based entirely on
convolutional neural networks. We demonstrate experimentally that this
architecture captures long-range dependencies in a document and recognizes
pertinent content, outperforming an oracle extractive system and
state-of-the-art abstractive approaches when evaluated automatically and by
humans.