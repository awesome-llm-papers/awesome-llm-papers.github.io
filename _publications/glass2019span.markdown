---
layout: publication
title: Span Selection Pre-training For Question Answering
authors: Michael Glass et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
citations: 19
bibkey: glass2019span
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.04120'}]
tags: [Model Architecture, Transformer, Masked Language Model, Reinforcement Learning,
  Pre-Training, BERT, Training Techniques, Evaluation]
---
BERT (Bidirectional Encoder Representations from Transformers) and related
pre-trained Transformers have provided large gains across many language
understanding tasks, achieving a new state-of-the-art (SOTA). BERT is
pre-trained on two auxiliary tasks: Masked Language Model and Next Sentence
Prediction. In this paper we introduce a new pre-training task inspired by
reading comprehension to better align the pre-training from memorization to
understanding. Span Selection Pre-Training (SSPT) poses cloze-like training
instances, but rather than draw the answer from the model's parameters, it is
selected from a relevant passage. We find significant and consistent
improvements over both BERT-BASE and BERT-LARGE on multiple reading
comprehension (MRC) datasets. Specifically, our proposed model has strong
empirical evidence as it obtains SOTA results on Natural Questions, a new
benchmark MRC dataset, outperforming BERT-LARGE by 3 F1 points on short answer
prediction. We also show significant impact in HotpotQA, improving answer
prediction F1 by 4 points and supporting fact prediction F1 by 1 point and
outperforming the previous best system. Moreover, we show that our pre-training
approach is particularly effective when training data is limited, improving the
learning curve by a large amount.