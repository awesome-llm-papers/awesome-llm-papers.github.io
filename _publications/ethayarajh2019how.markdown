---
layout: publication
title: How Contextual Are Contextualized Word Representations? Comparing The Geometry
  Of BERT, Elmo, And GPT-2 Embeddings
authors: Ethayarajh Kawin
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: ethayarajh2019how
citations: 306
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00512'}]
tags: [RAG, EMNLP, GPT, BERT, Model Architecture]
---
Replacing static word embeddings with contextualized word representations has
yielded significant improvements on many NLP tasks. However, just how
contextual are the contextualized representations produced by models such as
ELMo and BERT? Are there infinitely many context-specific representations for
each word, or are words essentially assigned one of a finite number of
word-sense representations? For one, we find that the contextualized
representations of all words are not isotropic in any layer of the
contextualizing model. While representations of the same word in different
contexts still have a greater cosine similarity than those of two different
words, this self-similarity is much lower in upper layers. This suggests that
upper layers of contextualizing models produce more context-specific
representations, much like how upper layers of LSTMs produce more task-specific
representations. In all layers of ELMo, BERT, and GPT-2, on average, less than
5% of the variance in a word's contextualized representations can be explained
by a static embedding for that word, providing some justification for the
success of contextualized representations.