---
layout: publication
title: 'MEMEN: Multi-layer Embedding With Memory Networks For Machine Comprehension'
authors: Boyuan Pan, Hao Li, Zhou Zhao, Bin Cao, Deng Cai, Xiaofei He
conference: Arxiv
year: 2017
bibkey: pan2017memen
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.09098'}]
tags: ["Model Architecture"]
short_authors: Pan et al.
---
Machine comprehension(MC) style question answering is a representative
problem in natural language processing. Previous methods rarely spend time on
the improvement of encoding layer, especially the embedding of syntactic
information and name entity of the words, which are very crucial to the quality
of encoding. Moreover, existing attention methods represent each query word as
a vector or use a single vector to represent the whole query sentence, neither
of them can handle the proper weight of the key words in query sentence. In
this paper, we introduce a novel neural network architecture called Multi-layer
Embedding with Memory Network(MEMEN) for machine reading task. In the encoding
layer, we employ classic skip-gram model to the syntactic and semantic
information of the words to train a new kind of embedding layer. We also
propose a memory network of full-orientation matching of the query and passage
to catch more pivotal information. Experiments show that our model has
competitive results both from the perspectives of precision and efficiency in
Stanford Question Answering Dataset(SQuAD) among all published results and
achieves the state-of-the-art results on TriviaQA dataset.