---
layout: publication
title: A Simple Method For Commonsense Reasoning
authors: Trieu H. Trinh, Quoc V. Le
conference: Arxiv
year: 2018
bibkey: trinh2018simple
citations: 341
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.02847'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Trieu H. Trinh, Quoc V. Le
---
Commonsense reasoning is a long-standing challenge for deep learning. For
example, it is difficult to use neural networks to tackle the Winograd Schema
dataset (Levesque et al., 2011). In this paper, we present a simple method for
commonsense reasoning with neural networks, using unsupervised learning. Key to
our method is the use of language models, trained on a massive amount of
unlabled data, to score multiple choice questions posed by commonsense
reasoning tests. On both Pronoun Disambiguation and Winograd Schema challenges,
our models outperform previous state-of-the-art methods by a large margin,
without using expensive annotated knowledge bases or hand-engineered features.
We train an array of large RNN language models that operate at word or
character level on LM-1-Billion, CommonCrawl, SQuAD, Gutenberg Books, and a
customized corpus for this task and show that diversity of training data plays
an important role in test performance. Further analysis also shows that our
system successfully discovers important features of the context that decide the
correct answer, indicating a good grasp of commonsense knowledge.