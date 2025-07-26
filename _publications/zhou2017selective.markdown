---
layout: publication
title: Selective Encoding For Abstractive Sentence Summarization
authors: Qingyu Zhou, Nan Yang, Furu Wei, Ming Zhou
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: zhou2017selective
citations: 233
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.07073'}]
tags: ["Datasets", "Tools"]
short_authors: Zhou et al.
---
We propose a selective encoding model to extend the sequence-to-sequence
framework for abstractive sentence summarization. It consists of a sentence
encoder, a selective gate network, and an attention equipped decoder. The
sentence encoder and decoder are built with recurrent neural networks. The
selective gate network constructs a second level sentence representation by
controlling the information flow from encoder to decoder. The second level
representation is tailored for sentence summarization task, which leads to
better performance. We evaluate our model on the English Gigaword, DUC 2004 and
MSR abstractive sentence summarization datasets. The experimental results show
that the proposed selective encoding model outperforms the state-of-the-art
baseline models.