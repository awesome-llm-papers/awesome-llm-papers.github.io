---
layout: publication
title: Representation Degeneration Problem In Training Natural Language Generation
  Models
authors: Gao et al.
conference: Arxiv
year: 2019
bibkey: gao2019representation
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.12009'}]
tags: [Language Modeling, Training Techniques, Datasets]
---
We study an interesting problem in training neural network-based models for
natural language generation tasks, which we call the *representation
degeneration problem*. We observe that when training a model for natural
language generation tasks through likelihood maximization with the weight tying
trick, especially with big training datasets, most of the learnt word
embeddings tend to degenerate and be distributed into a narrow cone, which
largely limits the representation power of word embeddings. We analyze the
conditions and causes of this problem and propose a novel regularization method
to address it. Experiments on language modeling and machine translation show
that our method can largely mitigate the representation degeneration problem
and achieve better performance than baseline algorithms.