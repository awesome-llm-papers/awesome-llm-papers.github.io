---
layout: publication
title: A Surprisingly Robust Trick For Winograd Schema Challenge
authors: Vid Kocijan, Ana-maria Cretu, Oana-maria Camburu, Yordan Yordanov, Thomas
  Lukasiewicz
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: kocijan2019surprisingly
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.06290'}]
tags: ["Datasets", "Fine-Tuning", "Model Architecture"]
short_authors: Kocijan et al.
---
The Winograd Schema Challenge (WSC) dataset WSC273 and its inference
counterpart WNLI are popular benchmarks for natural language understanding and
commonsense reasoning. In this paper, we show that the performance of three
language models on WSC273 strongly improves when fine-tuned on a similar
pronoun disambiguation problem dataset (denoted WSCR). We additionally generate
a large unsupervised WSC-like dataset. By fine-tuning the BERT language model
both on the introduced and on the WSCR dataset, we achieve overall accuracies
of 72.5% and 74.7% on WSC273 and WNLI, improving the previous state-of-the-art
solutions by 8.8% and 9.6%, respectively. Furthermore, our fine-tuned models
are also consistently more robust on the "complex" subsets of WSC273,
introduced by Trichelair et al. (2018).