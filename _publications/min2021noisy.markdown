---
layout: publication
title: Noisy Channel Language Model Prompting For Few-shot Text Classification
authors: Sewon Min, Mike Lewis, Hannaneh Hajishirzi, Luke Zettlemoyer
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: min2021noisy
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.04106'}]
tags: ["Few-Shot", "Prompting"]
short_authors: Min et al.
---
We introduce a noisy channel approach for language model prompting in
few-shot text classification. Instead of computing the likelihood of the label
given the input (referred as direct models), channel models compute the
conditional probability of the input given the label, and are thereby required
to explain every word in the input. We use channel models for recently proposed
few-shot learning methods with no or very limited updates to the language model
parameters, via either in-context demonstration or prompt tuning. Our
experiments show that, for both methods, channel models significantly
outperform their direct counterparts, which we attribute to their stability,
i.e., lower variance and higher worst-case accuracy. We also present extensive
ablations that provide recommendations for when to use channel prompt tuning
instead of other competitive methods (e.g., direct head tuning): channel prompt
tuning is preferred when the number of training examples is small, labels in
the training data are imbalanced, or generalization to unseen labels is
required.