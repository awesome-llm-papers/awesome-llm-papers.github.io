---
layout: publication
title: 'Sentence-bert: Sentence Embeddings Using Siamese Bert-networks'
authors: Nils Reimers, Iryna Gurevych
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: reimers2019sentence
citations: 7625
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.10084'}]
tags: ["EMNLP", "Fine-Tuning", "Model Architecture"]
short_authors: Nils Reimers, Iryna Gurevych
---
BERT (Devlin et al., 2018) and RoBERTa (Liu et al., 2019) has set a new
state-of-the-art performance on sentence-pair regression tasks like semantic
textual similarity (STS). However, it requires that both sentences are fed into
the network, which causes a massive computational overhead: Finding the most
similar pair in a collection of 10,000 sentences requires about 50 million
inference computations (~65 hours) with BERT. The construction of BERT makes it
unsuitable for semantic similarity search as well as for unsupervised tasks
like clustering.
  In this publication, we present Sentence-BERT (SBERT), a modification of the
pretrained BERT network that use siamese and triplet network structures to
derive semantically meaningful sentence embeddings that can be compared using
cosine-similarity. This reduces the effort for finding the most similar pair
from 65 hours with BERT / RoBERTa to about 5 seconds with SBERT, while
maintaining the accuracy from BERT.
  We evaluate SBERT and SRoBERTa on common STS tasks and transfer learning
tasks, where it outperforms other state-of-the-art sentence embeddings methods.