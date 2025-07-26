---
layout: publication
title: 'BAE: Bert-based Adversarial Examples For Text Classification'
authors: Siddhant Garg, Goutham Ramakrishnan
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: garg2020bae
citations: 390
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.01970'}]
tags: ["EMNLP", "Model Architecture", "Security"]
short_authors: Siddhant Garg, Goutham Ramakrishnan
---
Modern text classification models are susceptible to adversarial examples,
perturbed versions of the original text indiscernible by humans which get
misclassified by the model. Recent works in NLP use rule-based synonym
replacement strategies to generate adversarial examples. These strategies can
lead to out-of-context and unnaturally complex token replacements, which are
easily identifiable by humans. We present BAE, a black box attack for
generating adversarial examples using contextual perturbations from a BERT
masked language model. BAE replaces and inserts tokens in the original text by
masking a portion of the text and leveraging the BERT-MLM to generate
alternatives for the masked tokens. Through automatic and human evaluations, we
show that BAE performs a stronger attack, in addition to generating adversarial
examples with improved grammaticality and semantic coherence as compared to
prior work.