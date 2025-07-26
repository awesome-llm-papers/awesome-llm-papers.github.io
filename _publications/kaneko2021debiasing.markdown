---
layout: publication
title: Debiasing Pre-trained Contextualised Embeddings
authors: Masahiro Kaneko, Danushka Bollegala
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2021
bibkey: kaneko2021debiasing
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.09523'}]
tags: ["EACL", "Ethics & Fairness", "Evaluation", "Fine-Tuning"]
short_authors: Masahiro Kaneko, Danushka Bollegala
---
In comparison to the numerous debiasing methods proposed for the static
non-contextualised word embeddings, the discriminative biases in contextualised
embeddings have received relatively little attention. We propose a fine-tuning
method that can be applied at token- or sentence-levels to debias pre-trained
contextualised embeddings. Our proposed method can be applied to any
pre-trained contextualised embedding model, without requiring to retrain those
models. Using gender bias as an illustrative example, we then conduct a
systematic study using several state-of-the-art (SoTA) contextualised
representations on multiple benchmark datasets to evaluate the level of biases
encoded in different contextualised embeddings before and after debiasing using
the proposed method. We find that applying token-level debiasing for all tokens
and across all layers of a contextualised embedding model produces the best
performance. Interestingly, we observe that there is a trade-off between
creating an accurate vs. unbiased contextualised embedding model, and different
contextualised embedding models respond differently to this trade-off.