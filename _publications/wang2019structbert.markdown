---
layout: publication
title: 'Structbert: Incorporating Language Structures Into Pre-training For Deep Language
  Understanding'
authors: Wei Wang, Bin Bi, Ming Yan, Chen Wu, Zuyi Bao, Jiangnan Xia, Liwei Peng,
  Luo Si
conference: Arxiv
year: 2019
bibkey: wang2019structbert
citations: 138
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.04577'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Wang et al.
---
Recently, the pre-trained language model, BERT (and its robustly optimized
version RoBERTa), has attracted a lot of attention in natural language
understanding (NLU), and achieved state-of-the-art accuracy in various NLU
tasks, such as sentiment classification, natural language inference, semantic
textual similarity and question answering. Inspired by the linearization
exploration work of Elman [8], we extend BERT to a new model, StructBERT, by
incorporating language structures into pre-training. Specifically, we pre-train
StructBERT with two auxiliary tasks to make the most of the sequential order of
words and sentences, which leverage language structures at the word and
sentence levels, respectively. As a result, the new model is adapted to
different levels of language understanding required by downstream tasks. The
StructBERT with structural pre-training gives surprisingly good empirical
results on a variety of downstream tasks, including pushing the
state-of-the-art on the GLUE benchmark to 89.0 (outperforming all published
models), the F1 score on SQuAD v1.1 question answering to 93.0, the accuracy on
SNLI to 91.7.