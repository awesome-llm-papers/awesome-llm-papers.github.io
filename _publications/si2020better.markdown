---
layout: publication
title: 'Better Robustness By More Coverage: Adversarial Training With Mixup Augmentation
  For Robust Fine-tuning'
authors: Chenglei Si et al.
conference: Arxiv
year: 2020
citations: 21
bibkey: si2020better
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15699'}, {name: Code,
    url: 'https://github.com/thunlp/MixADA'}]
tags: [Training Techniques, RAG, Fine-Tuning, Reinforcement Learning, BERT, Has Code,
  Security, Model Architecture]
---
Pretrained language models (PLMs) perform poorly under adversarial attacks.
To improve the adversarial robustness, adversarial data augmentation (ADA) has
been widely adopted to cover more search space of adversarial attacks by adding
textual adversarial examples during training. However, the number of
adversarial examples for text augmentation is still extremely insufficient due
to the exponentially large attack search space. In this work, we propose a
simple and effective method to cover a much larger proportion of the attack
search space, called Adversarial and Mixup Data Augmentation (AMDA).
Specifically, AMDA linearly interpolates the representations of pairs of
training samples to form new virtual samples, which are more abundant and
diverse than the discrete text adversarial examples in conventional ADA.
Moreover, to fairly evaluate the robustness of different models, we adopt a
challenging evaluation setup, which generates a new set of adversarial examples
targeting each model. In text classification experiments of BERT and RoBERTa,
AMDA achieves significant robustness gains under two strong adversarial attacks
and alleviates the performance degradation of ADA on the clean data. Our code
is available at: https://github.com/thunlp/MixADA .