---
layout: publication
title: 'Charagram: Embedding Words And Sentences Via Character N-grams'
authors: Wieting et al.
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: wieting2016charagram
citations: 180
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1607.02789'}]
tags: [Model Architecture, RAG, EMNLP, Evaluation]
---
We present Charagram embeddings, a simple approach for learning
character-based compositional models to embed textual sequences. A word or
sentence is represented using a character n-gram count vector, followed by a
single nonlinear transformation to yield a low-dimensional embedding. We use
three tasks for evaluation: word similarity, sentence similarity, and
part-of-speech tagging. We demonstrate that Charagram embeddings outperform
more complex architectures based on character-level recurrent and convolutional
neural networks, achieving new state-of-the-art performance on several
similarity tasks.