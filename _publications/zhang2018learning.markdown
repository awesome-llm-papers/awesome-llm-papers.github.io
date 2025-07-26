---
layout: publication
title: Learning Universal Sentence Representations With Mean-max Attention Autoencoder
authors: Minghua Zhang, Yunfang Wu, Weikang Li, Wei Li
conference: Proceedings of the Ninth International Workshop on Health Text Mining
  and Information Analysis
year: 2018
bibkey: zhang2018learning
citations: 117
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.06590'}]
tags: ["Model Architecture", "Tools"]
short_authors: Zhang et al.
---
In order to learn universal sentence representations, previous methods focus
on complex recurrent neural networks or supervised learning. In this paper, we
propose a mean-max attention autoencoder (mean-max AAE) within the
encoder-decoder framework. Our autoencoder rely entirely on the MultiHead
self-attention mechanism to reconstruct the input sequence. In the encoding we
propose a mean-max strategy that applies both mean and max pooling operations
over the hidden vectors to capture diverse information of the input. To enable
the information to steer the reconstruction process dynamically, the decoder
performs attention over the mean-max representation. By training our model on a
large collection of unlabelled data, we obtain high-quality representations of
sentences. Experimental results on a broad range of 10 transfer tasks
demonstrate that our model outperforms the state-of-the-art unsupervised single
methods, including the classical skip-thoughts and the advanced
skip-thoughts+LN model. Furthermore, compared with the traditional recurrent
neural network, our mean-max AAE greatly reduce the training time.