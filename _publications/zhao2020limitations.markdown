---
layout: publication
title: On The Limitations Of Cross-lingual Encoders As Exposed By Reference-free Machine
  Translation Evaluation
authors: Zhao et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: zhao2020limitations
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.01196'}]
tags: [Security, Model Architecture, BERT, Evaluation, ACL, Reinforcement Learning]
---
Evaluation of cross-lingual encoders is usually performed either via
zero-shot cross-lingual transfer in supervised downstream tasks or via
unsupervised cross-lingual textual similarity. In this paper, we concern
ourselves with reference-free machine translation (MT) evaluation where we
directly compare source texts to (sometimes low-quality) system translations,
which represents a natural adversarial setup for multilingual encoders.
Reference-free evaluation holds the promise of web-scale comparison of MT
systems. We systematically investigate a range of metrics based on
state-of-the-art cross-lingual semantic representations obtained with
pretrained M-BERT and LASER. We find that they perform poorly as semantic
encoders for reference-free MT evaluation and identify their two key
limitations, namely, (a) a semantic mismatch between representations of mutual
translations and, more prominently, (b) the inability to punish
"translationese", i.e., low-quality literal translations. We propose two
partial remedies: (1) post-hoc re-alignment of the vector spaces and (2)
coupling of semantic-similarity based metrics with target-side language
modeling. In segment-level MT evaluation, our best metric surpasses
reference-based BLEU by 5.7 correlation points.