---
layout: publication
title: Self-training Improves Pre-training For Natural Language Understanding
authors: Jingfei Du, Edouard Grave, Beliz Gunel, Vishrav Chaudhary, Onur Celebi, Michael
  Auli, Ves Stoyanov, Alexis Conneau
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: du2020self
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.02194'}]
tags: ["Few-Shot", "NAACL", "Training Techniques"]
short_authors: Du et al.
---
Unsupervised pre-training has led to much recent progress in natural language
understanding. In this paper, we study self-training as another way to leverage
unlabeled data through semi-supervised learning. To obtain additional data for
a specific task, we introduce SentAugment, a data augmentation method which
computes task-specific query embeddings from labeled data to retrieve sentences
from a bank of billions of unlabeled sentences crawled from the web. Unlike
previous semi-supervised methods, our approach does not require in-domain
unlabeled data and is therefore more generally applicable. Experiments show
that self-training is complementary to strong RoBERTa baselines on a variety of
tasks. Our augmentation approach leads to scalable and effective self-training
with improvements of up to 2.6% on standard text classification benchmarks.
Finally, we also show strong gains on knowledge-distillation and few-shot
learning.