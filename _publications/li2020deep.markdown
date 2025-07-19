---
layout: publication
title: Deep Entity Matching With Pre-trained Language Models
authors: Li et al.
conference: Proceedings of the VLDB Endowment
year: 2020
bibkey: li2020deep
citations: 279
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.00584'}]
tags: [RAG, Training Techniques, Evaluation, BERT, Transformer, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning, Datasets]
---
We present Ditto, a novel entity matching system based on pre-trained
Transformer-based language models. We fine-tune and cast EM as a sequence-pair
classification problem to leverage such models with a simple architecture. Our
experiments show that a straightforward application of language models such as
BERT, DistilBERT, or RoBERTa pre-trained on large text corpora already
significantly improves the matching quality and outperforms previous
state-of-the-art (SOTA), by up to 29% of F1 score on benchmark datasets. We
also developed three optimization techniques to further improve Ditto's
matching capability. Ditto allows domain knowledge to be injected by
highlighting important pieces of input information that may be of interest when
making matching decisions. Ditto also summarizes strings that are too long so
that only the essential information is retained and used for EM. Finally, Ditto
adapts a SOTA technique on data augmentation for text to EM to augment the
training data with (difficult) examples. This way, Ditto is forced to learn
"harder" to improve the model's matching capability. The optimizations we
developed further boost the performance of Ditto by up to 9.8%. Perhaps more
surprisingly, we establish that Ditto can achieve the previous SOTA results
with at most half the number of labeled data. Finally, we demonstrate Ditto's
effectiveness on a real-world large-scale EM task. On matching two company
datasets consisting of 789K and 412K records, Ditto achieves a high F1 score of
96.5%.