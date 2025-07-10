---
layout: publication
title: Long-span Summarization Via Local Attention And Content Selection
authors: Potsawee Manakul, Mark J. F. Gales
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
citations: 17
bibkey: manakul2021long
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.03801'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Fine-Tuning, Arxiv, Training
    Techniques]
---
Transformer-based models have achieved state-of-the-art results in a wide
range of natural language processing (NLP) tasks including document
summarization. Typically these systems are trained by fine-tuning a large
pre-trained model to the target task. One issue with these transformer-based
models is that they do not scale well in terms of memory and compute
requirements as the input length grows. Thus, for long document summarization,
it can be challenging to train or fine-tune these models. In this work, we
exploit large pre-trained transformer-based models and address long-span
dependencies in abstractive summarization using two methods: local
self-attention; and explicit content selection. These approaches are compared
on a range of network configurations. Experiments are carried out on standard
long-span summarization tasks, including Spotify Podcast, arXiv, and PubMed
datasets. We demonstrate that by combining these methods, we can achieve
state-of-the-art results on all three tasks in the ROUGE scores. Moreover,
without a large-scale GPU card, our approach can achieve comparable or better
results than existing approaches.