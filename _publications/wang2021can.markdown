---
layout: publication
title: Can Generative Pre-trained Language Models Serve As Knowledge Bases For Closed-book
  QA?
authors: Wang Cunxiang, Liu Pai, Zhang Yue
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: wang2021can
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.01561'}]
tags: [Training Techniques, Evaluation, ACL, Datasets, Reinforcement Learning]
---
Recent work has investigated the interesting question using pre-trained
language models (PLMs) as knowledge bases for answering open questions.
However, existing work is limited in using small benchmarks with high
test-train overlaps. We construct a new dataset of closed-book QA using SQuAD,
and investigate the performance of BART. Experiments show that it is
challenging for BART to remember training facts in high precision, and also
challenging to answer closed-book questions even if relevant knowledge is
retained. Some promising directions are found, including decoupling the
knowledge memorizing process and the QA finetune process, forcing the model to
recall relevant knowledge when question answering.