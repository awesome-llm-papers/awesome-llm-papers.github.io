---
layout: publication
title: 'Ernie-gram: Pre-training With Explicitly N-gram Masked Language Modeling For
  Natural Language Understanding'
authors: Dongling Xiao, Yu-kun Li, Han Zhang, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang
conference: Proceedings of the Twenty-Ninth International Joint Conference on Artificial
  Intelligence
year: 2020
bibkey: xiao2020ernie
citations: 98
additional_links: [{name: Code, url: 'https://github.com/PaddlePaddle/ERNIE'}, {name: Paper,
    url: 'https://arxiv.org/abs/2010.12148'}]
tags: ["IJCAI", "Model Architecture", "Training Techniques"]
short_authors: Xiao et al.
---
Coarse-grained linguistic information, such as named entities or phrases,
facilitates adequately representation learning in pre-training. Previous works
mainly focus on extending the objective of BERT's Masked Language Modeling
(MLM) from masking individual tokens to contiguous sequences of n tokens. We
argue that such contiguously masking method neglects to model the
intra-dependencies and inter-relation of coarse-grained linguistic information.
As an alternative, we propose ERNIE-Gram, an explicitly n-gram masking method
to enhance the integration of coarse-grained information into pre-training. In
ERNIE-Gram, n-grams are masked and predicted directly using explicit n-gram
identities rather than contiguous sequences of n tokens. Furthermore,
ERNIE-Gram employs a generator model to sample plausible n-gram identities as
optional n-gram masks and predict them in both coarse-grained and fine-grained
manners to enable comprehensive n-gram prediction and relation modeling. We
pre-train ERNIE-Gram on English and Chinese text corpora and fine-tune on 19
downstream tasks. Experimental results show that ERNIE-Gram outperforms
previous pre-training models like XLNet and RoBERTa by a large margin, and
achieves comparable results with state-of-the-art methods. The source codes and
pre-trained models have been released at https://github.com/PaddlePaddle/ERNIE.