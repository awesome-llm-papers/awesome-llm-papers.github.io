---
layout: publication
title: 'Advaug: Robust Adversarial Augmentation For Neural Machine Translation'
authors: Cheng et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: cheng2020advaug
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.11834'}]
tags: [Security, Model Architecture, Training Techniques, Evaluation, ACL, Transformer,
  Datasets]
---
In this paper, we propose a new adversarial augmentation method for Neural
Machine Translation (NMT). The main idea is to minimize the vicinal risk over
virtual sentences sampled from two vicinity distributions, of which the crucial
one is a novel vicinity distribution for adversarial sentences that describes a
smooth interpolated embedding space centered around observed training sentence
pairs. We then discuss our approach, AdvAug, to train NMT models using the
embeddings of virtual sentences in sequence-to-sequence learning. Experiments
on Chinese-English, English-French, and English-German translation benchmarks
show that AdvAug achieves significant improvements over the Transformer (up to
4.9 BLEU points), and substantially outperforms other data augmentation
techniques (e.g. back-translation) without using extra corpora.