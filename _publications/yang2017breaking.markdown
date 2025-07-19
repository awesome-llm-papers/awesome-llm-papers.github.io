---
layout: publication
title: 'Breaking The Softmax Bottleneck: A High-rank RNN Language Model'
authors: Yang et al.
conference: Arxiv
year: 2017
bibkey: yang2017breaking
citations: 270
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.03953'}]
tags: [Language Modeling, Datasets]
---
We formulate language modeling as a matrix factorization problem, and show
that the expressiveness of Softmax-based models (including the majority of
neural language models) is limited by a Softmax bottleneck. Given that natural
language is highly context-dependent, this further implies that in practice
Softmax with distributed word embeddings does not have enough capacity to model
natural language. We propose a simple and effective method to address this
issue, and improve the state-of-the-art perplexities on Penn Treebank and
WikiText-2 to 47.69 and 40.68 respectively. The proposed method also excels on
the large-scale 1B Word dataset, outperforming the baseline by over 5.6 points
in perplexity.