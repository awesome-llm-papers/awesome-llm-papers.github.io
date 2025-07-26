---
layout: publication
title: 'W2v-bert: Combining Contrastive Learning And Masked Language Modeling For
  Self-supervised Speech Pre-training'
authors: Yu-an Chung, Yu Zhang, Wei Han, Chung-cheng Chiu, James Qin, Ruoming Pang,
  Yonghui Wu
conference: 2021 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
year: 2021
bibkey: chung2021w2v
citations: 190
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.06209'}]
tags: ["ASRU", "Model Architecture", "Training Techniques"]
short_authors: Chung et al.
---
Motivated by the success of masked language modeling~(MLM) in pre-training
natural language processing models, we propose w2v-BERT that explores MLM for
self-supervised speech representation learning. w2v-BERT is a framework that
combines contrastive learning and MLM, where the former trains the model to
discretize input continuous speech signals into a finite set of discriminative
speech tokens, and the latter trains the model to learn contextualized speech
representations via solving a masked prediction task consuming the discretized
tokens. In contrast to existing MLM-based speech pre-training frameworks such
as HuBERT, which relies on an iterative re-clustering and re-training process,
or vq-wav2vec, which concatenates two separately trained modules, w2v-BERT can
be optimized in an end-to-end fashion by solving the two self-supervised
tasks~(the contrastive task and MLM) simultaneously. Our experiments show that
w2v-BERT achieves competitive results compared to current state-of-the-art
pre-trained models on the LibriSpeech benchmarks when using the Libri-Light~60k
corpus as the unsupervised data. In particular, when compared to published
models such as conformer-based wav2vec~2.0 and HuBERT, our model shows~5%
to~10% relative WER reduction on the test-clean and test-other subsets. When
applied to the Google's Voice Search traffic dataset, w2v-BERT outperforms our
internal conformer-based wav2vec~2.0 by more than~30% relatively.