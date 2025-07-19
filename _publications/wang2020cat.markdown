---
layout: publication
title: 'Cat-gen: Improving Robustness In NLP Models Via Controlled Adversarial Text
  Generation'
authors: Wang et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: wang2020cat
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.02338'}]
tags: [Training Techniques, EMNLP, Model Architecture, Language Modeling, Reinforcement
    Learning, Security, Datasets]
---
NLP models are shown to suffer from robustness issues, i.e., a model's
prediction can be easily changed under small perturbations to the input. In
this work, we present a Controlled Adversarial Text Generation (CAT-Gen) model
that, given an input text, generates adversarial texts through controllable
attributes that are known to be invariant to task labels. For example, in order
to attack a model for sentiment classification over product reviews, we can use
the product categories as the controllable attribute which would not change the
sentiment of the reviews. Experiments on real-world NLP datasets demonstrate
that our method can generate more diverse and fluent adversarial texts,
compared to many existing adversarial text generation approaches. We further
use our generated adversarial examples to improve models through adversarial
training, and we demonstrate that our generated attacks are more robust against
model re-training and different model architectures.