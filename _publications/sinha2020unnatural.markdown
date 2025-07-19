---
layout: publication
title: Unnatural Language Inference
authors: Sinha et al.
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2020
bibkey: sinha2020unnatural
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.00010'}]
tags: [Model Architecture, Evaluation, ACL, Transformer, Datasets]
---
Recent investigations into the inner-workings of state-of-the-art large-scale
pre-trained Transformer-based Natural Language Understanding (NLU) models
indicate that they appear to know humanlike syntax, at least to some extent. We
provide novel evidence that complicates this claim: we find that
state-of-the-art Natural Language Inference (NLI) models assign the same labels
to permuted examples as they do to the original, i.e. they are largely
invariant to random word-order permutations. This behavior notably differs from
that of humans; we struggle with ungrammatical sentences. To measure the
severity of this issue, we propose a suite of metrics and investigate which
properties of particular permutations lead models to be word-order invariant.
In the MNLI dataset, for example, we find almost all (98.7%) examples contain
at least one permutation which elicits the gold label. Models are sometimes
even able to assign gold labels to permutations that they originally failed to
predict correctly. We provide a comprehensive empirical evaluation of this
phenomenon, and further show that this issue exists for both Transformers and
pre-Transformer RNN / ConvNet based encoders, as well as across multiple
languages (English and Mandarin Chinese). Our code and data are available at
https://github.com/facebookresearch/unlu.