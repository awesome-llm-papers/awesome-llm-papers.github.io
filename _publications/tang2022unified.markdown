---
layout: publication
title: Unified Speech-text Pre-training For Speech Translation And Recognition
authors: Tang et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: tang2022unified
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.05409'}]
tags: [Tools, Training Techniques, ACL, RAG, Datasets]
---
We describe a method to jointly pre-train speech and text in an
encoder-decoder modeling framework for speech translation and recognition. The
proposed method incorporates four self-supervised and supervised subtasks for
cross modality learning. A self-supervised speech subtask leverages unlabelled
speech data, and a (self-)supervised text to text subtask makes use of abundant
text training data. Two auxiliary supervised speech tasks are included to unify
speech and text modeling space. Our contribution lies in integrating linguistic
information from the text corpus into the speech pre-training. Detailed
analysis reveals learning interference among subtasks. Two pre-training
configurations for speech translation and recognition, respectively, are
presented to alleviate subtask interference. Our experiments show the proposed
method can effectively fuse speech and text information into one model. It
achieves between 1.7 and 2.3 BLEU improvement above the state of the art on the
MuST-C speech translation dataset and comparable WERs to wav2vec 2.0 on the
Librispeech speech recognition task.