---
layout: publication
title: Masked Language Model Scoring
authors: Julian Salazar, Davis Liang, Toan Q. Nguyen, Katrin Kirchhoff
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics (2020) 2699-2712
year: 2019
citations: 119
bibkey: salazar2019masked
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.14659'}, {name: Code,
    url: 'https://github.com/awslabs/mlm-scoring'}]
tags: [Ethics and Bias, Masked Language Model, GPT, Fine-Tuning, Tools, BERT, Has
    Code, Model Architecture]
---
Pretrained masked language models (MLMs) require finetuning for most NLP
tasks. Instead, we evaluate MLMs out of the box via their pseudo-log-likelihood
scores (PLLs), which are computed by masking tokens one by one. We show that
PLLs outperform scores from autoregressive language models like GPT-2 in a
variety of tasks. By rescoring ASR and NMT hypotheses, RoBERTa reduces an
end-to-end LibriSpeech model's WER by 30% relative and adds up to +1.7 BLEU on
state-of-the-art baselines for low-resource translation pairs, with further
gains from domain adaptation. We attribute this success to PLL's unsupervised
expression of linguistic acceptability without a left-to-right bias, greatly
improving on scores from GPT-2 (+10 points on island effects, NPI licensing in
BLiMP). One can finetune MLMs to give scores without masking, enabling
computation in a single inference pass. In all, PLLs and their associated
pseudo-perplexities (PPPLs) enable plug-and-play use of the growing number of
pretrained MLMs; e.g., we use a single cross-lingual model to rescore
translations in multiple languages. We release our library for language model
scoring at https://github.com/awslabs/mlm-scoring.