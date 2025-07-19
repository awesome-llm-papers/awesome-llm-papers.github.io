---
layout: publication
title: Deep Neural Machine Translation With Linear Associative Unit
authors: Wang et al.
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: wang2017deep
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.00861'}]
tags: [ACL, Model Architecture, Efficiency And Optimization, Merging]
---
Deep Neural Networks (DNNs) have provably enhanced the state-of-the-art
Neural Machine Translation (NMT) with their capability in modeling complex
functions and capturing complex linguistic structures. However NMT systems with
deep architecture in their encoder or decoder RNNs often suffer from severe
gradient diffusion due to the non-linear recurrent activations, which often
make the optimization much more difficult. To address this problem we propose
novel linear associative units (LAU) to reduce the gradient propagation length
inside the recurrent unit. Different from conventional approaches (LSTM unit
and GRU), LAUs utilizes linear associative connections between input and output
of the recurrent unit, which allows unimpeded information flow through both
space and time direction. The model is quite simple, but it is surprisingly
effective. Our empirical study on Chinese-English translation shows that our
model with proper configuration can improve by 11.7 BLEU upon Groundhog and the
best reported results in the same setting. On WMT14 English-German task and a
larger WMT14 English-French task, our model achieves comparable results with
the state-of-the-art.