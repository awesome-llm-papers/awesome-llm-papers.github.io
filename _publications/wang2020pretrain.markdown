---
layout: publication
title: 'To Pretrain Or Not To Pretrain: Examining The Benefits Of Pretraining On Resource
  Rich Tasks'
authors: Sinong Wang, Madian Khabsa, Hao Ma
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
citations: 15
bibkey: wang2020pretrain
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.08671'}]
tags: [BERT, Training Techniques, Model Architecture, Masked Language Model]
---
Pretraining NLP models with variants of Masked Language Model (MLM)
objectives has recently led to a significant improvements on many tasks. This
paper examines the benefits of pretrained models as a function of the number of
training samples used in the downstream task. On several text classification
tasks, we show that as the number of training examples grow into the millions,
the accuracy gap between finetuning BERT-based model and training vanilla LSTM
from scratch narrows to within 1%. Our findings indicate that MLM-based models
might reach a diminishing return point as the supervised data size increases
significantly.