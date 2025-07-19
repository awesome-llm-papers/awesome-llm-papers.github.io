---
layout: publication
title: Multilingual Universal Sentence Encoder For Semantic Retrieval
authors: Yang et al.
conference: 'Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics: System Demonstrations'
year: 2019
bibkey: yang2019multilingual
citations: 374
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.04307'}]
tags: [ACL, Model Architecture, Transformer, Fine Tuning]
---
We introduce two pre-trained retrieval focused multilingual sentence encoding
models, respectively based on the Transformer and CNN model architectures. The
models embed text from 16 languages into a single semantic space using a
multi-task trained dual-encoder that learns tied representations using
translation based bridge tasks (Chidambaram al., 2018). The models provide
performance that is competitive with the state-of-the-art on: semantic
retrieval (SR), translation pair bitext retrieval (BR) and retrieval question
answering (ReQA). On English transfer learning tasks, our sentence-level
embeddings approach, and in some cases exceed, the performance of monolingual,
English only, sentence embedding models. Our models are made available for
download on TensorFlow Hub.