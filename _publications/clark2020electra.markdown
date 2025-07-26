---
layout: publication
title: 'ELECTRA: Pre-training Text Encoders As Discriminators Rather Than Generators'
authors: Kevin Clark, Minh-thang Luong, Quoc V. Le, Christopher D. Manning
conference: Arxiv
year: 2020
bibkey: clark2020electra
citations: 1598
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.10555'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Clark et al.
---
Masked language modeling (MLM) pre-training methods such as BERT corrupt the
input by replacing some tokens with [MASK] and then train a model to
reconstruct the original tokens. While they produce good results when
transferred to downstream NLP tasks, they generally require large amounts of
compute to be effective. As an alternative, we propose a more sample-efficient
pre-training task called replaced token detection. Instead of masking the
input, our approach corrupts it by replacing some tokens with plausible
alternatives sampled from a small generator network. Then, instead of training
a model that predicts the original identities of the corrupted tokens, we train
a discriminative model that predicts whether each token in the corrupted input
was replaced by a generator sample or not. Thorough experiments demonstrate
this new pre-training task is more efficient than MLM because the task is
defined over all input tokens rather than just the small subset that was masked
out. As a result, the contextual representations learned by our approach
substantially outperform the ones learned by BERT given the same model size,
data, and compute. The gains are particularly strong for small models; for
example, we train a model on one GPU for 4 days that outperforms GPT (trained
using 30x more compute) on the GLUE natural language understanding benchmark.
Our approach also works well at scale, where it performs comparably to RoBERTa
and XLNet while using less than 1/4 of their compute and outperforms them when
using the same amount of compute.