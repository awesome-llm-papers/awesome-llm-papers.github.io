---
layout: publication
title: Using Adversarial Attacks To Reveal The Statistical Bias In Machine Reading
  Comprehension Models
authors: Jieyu Lin, Jiajie Zou, Nai Ding
conference: Arxiv
year: 2021
citations: 15
bibkey: lin2021using
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.11136'}]
tags: [Ethics and Bias, Training Techniques, Reinforcement Learning, BERT, Security,
  Model Architecture]
---
Pre-trained language models have achieved human-level performance on many
Machine Reading Comprehension (MRC) tasks, but it remains unclear whether these
models truly understand language or answer questions by exploiting statistical
biases in datasets. Here, we demonstrate a simple yet effective method to
attack MRC models and reveal the statistical biases in these models. We apply
the method to the RACE dataset, for which the answer to each MRC question is
selected from 4 options. It is found that several pre-trained language models,
including BERT, ALBERT, and RoBERTa, show consistent preference to some
options, even when these options are irrelevant to the question. When
interfered by these irrelevant options, the performance of MRC models can be
reduced from human-level performance to the chance-level performance. Human
readers, however, are not clearly affected by these irrelevant options.
Finally, we propose an augmented training method that can greatly reduce
models' statistical biases.