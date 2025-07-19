---
layout: publication
title: How Do Source-side Monolingual Word Embeddings Impact Neural Machine Translation?
authors: Ding Shuoyang, Duh Kevin
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: ding2018how
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.01515'}]
tags: [Reinforcement Learning, Training Techniques, EMNLP]
---
Using pre-trained word embeddings as input layer is a common practice in many
natural language processing (NLP) tasks, but it is largely neglected for neural
machine translation (NMT). In this paper, we conducted a systematic analysis on
the effect of using pre-trained source-side monolingual word embedding in NMT.
We compared several strategies, such as fixing or updating the embeddings
during NMT training on varying amounts of data, and we also proposed a novel
strategy called dual-embedding that blends the fixing and updating strategies.
Our results suggest that pre-trained embeddings can be helpful if properly
incorporated into NMT, especially when parallel data is limited or additional
in-domain monolingual data is readily available.