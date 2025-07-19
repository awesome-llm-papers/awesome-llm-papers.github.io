---
layout: publication
title: Improving Dialog Evaluation With A Multi-reference Adversarial Dataset And
  Large Scale Pretraining
authors: Sai et al.
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: sai2020improving
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.11321'}]
tags: [Security, Model Architecture, Training Techniques, BERT, Evaluation, TACL,
  ACL, Datasets]
---
There is an increasing focus on model-based dialog evaluation metrics such as
ADEM, RUBER, and the more recent BERT-based metrics. These models aim to assign
a high score to all relevant responses and a low score to all irrelevant
responses. Ideally, such models should be trained using multiple relevant and
irrelevant responses for any given context. However, no such data is publicly
available, and hence existing models are usually trained using a single
relevant response and multiple randomly selected responses from other contexts
(random negatives). To allow for better training and robust evaluation of
model-based metrics, we introduce the DailyDialog++ dataset, consisting of (i)
five relevant responses for each context and (ii) five adversarially crafted
irrelevant responses for each context. Using this dataset, we first show that
even in the presence of multiple correct references, n-gram based metrics and
embedding based metrics do not perform well at separating relevant responses
from even random negatives. While model-based metrics perform better than
n-gram and embedding based metrics on random negatives, their performance drops
substantially when evaluated on adversarial examples. To check if large scale
pretraining could help, we propose a new BERT-based evaluation metric called
DEB, which is pretrained on 727M Reddit conversations and then finetuned on our
dataset. DEB significantly outperforms existing models, showing better
correlation with human judgements and better performance on random negatives
(88.27% accuracy). However, its performance again drops substantially, when
evaluated on adversarial responses, thereby highlighting that even large-scale
pretrained evaluation models are not robust to the adversarial examples in our
dataset. The dataset and code are publicly available.