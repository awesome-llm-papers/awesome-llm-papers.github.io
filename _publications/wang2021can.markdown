---
layout: publication
title: Can Generative Pre-trained Language Models Serve As Knowledge Bases For Closed-book
  QA?
authors: Cunxiang Wang, Pai Liu, Yue Zhang
conference: Arxiv
year: 2021
citations: 20
bibkey: wang2021can
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.01561'}]
tags: [Reinforcement Learning, Training Techniques]
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