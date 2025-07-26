---
layout: publication
title: Learning Generic Sentence Representations Using Convolutional Neural Networks
authors: Zhe Gan, Yunchen Pu, Ricardo Henao, Chunyuan Li, Xiaodong He, Lawrence Carin
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: gan2016learning
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.07897'}]
tags: ["EMNLP", "Evaluation", "Training Techniques"]
short_authors: Gan et al.
---
We propose a new encoder-decoder approach to learn distributed sentence
representations that are applicable to multiple purposes. The model is learned
by using a convolutional neural network as an encoder to map an input sentence
into a continuous vector, and using a long short-term memory recurrent neural
network as a decoder. Several tasks are considered, including sentence
reconstruction and future sentence prediction. Further, a hierarchical
encoder-decoder model is proposed to encode a sentence to predict multiple
future sentences. By training our models on a large collection of novels, we
obtain a highly generic convolutional sentence encoder that performs well in
practice. Experimental results on several benchmark datasets, and across a
broad range of applications, demonstrate the superiority of the proposed model
over competing methods.