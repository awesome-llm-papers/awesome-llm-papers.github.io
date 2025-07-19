---
layout: publication
title: 'AT-BERT: Adversarial Training BERT For Acronym Identification Winning Solution
  For SDU@AAAI-21'
authors: Zhu et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2021
bibkey: zhu2021bert
citations: 223
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.03700'}]
tags: [Training Techniques, EMNLP, BERT, Model Architecture, Reinforcement Learning,
  Security, Fine Tuning, AAAI, Datasets]
---
Acronym identification focuses on finding the acronyms and the phrases that
have been abbreviated, which is crucial for scientific document understanding
tasks. However, the limited size of manually annotated datasets hinders further
improvement for the problem. Recent breakthroughs of language models
pre-trained on large corpora clearly show that unsupervised pre-training can
vastly improve the performance of downstream tasks. In this paper, we present
an Adversarial Training BERT method named AT-BERT, our winning solution to
acronym identification task for Scientific Document Understanding (SDU)
Challenge of AAAI 2021. Specifically, the pre-trained BERT is adopted to
capture better semantic representation. Then we incorporate the FGM adversarial
training strategy into the fine-tuning of BERT, which makes the model more
robust and generalized. Furthermore, an ensemble mechanism is devised to
involve the representations learned from multiple BERT variants. Assembling all
these components together, the experimental results on the SciAI dataset show
that our proposed approach outperforms all other competitive state-of-the-art
methods.