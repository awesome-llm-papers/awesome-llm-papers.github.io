---
layout: publication
title: Robust Pre-training By Adversarial Contrastive Learning
authors: Ziyu Jiang, Tianlong Chen, Ting Chen, Zhangyang Wang
conference: Arxiv
year: 2020
bibkey: jiang2020robust
citations: 66
additional_links: [{name: Code, url: 'https://github.com/VITA-Group/Adversarial-Contrastive-Learning'},
  {name: Paper, url: 'https://arxiv.org/abs/2010.13337'}]
tags: ["Training Techniques"]
short_authors: Jiang et al.
---
Recent work has shown that, when integrated with adversarial training,
self-supervised pre-training can lead to state-of-the-art robustness In this
work, we improve robustness-aware self-supervised pre-training by learning
representations that are consistent under both data augmentations and
adversarial perturbations. Our approach leverages a recent contrastive learning
framework, which learns representations by maximizing feature consistency under
differently augmented views. This fits particularly well with the goal of
adversarial robustness, as one cause of adversarial fragility is the lack of
feature invariance, i.e., small input perturbations can result in undesirable
large changes in features or even predicted labels. We explore various options
to formulate the contrastive task, and demonstrate that by injecting
adversarial perturbations, contrastive pre-training can lead to models that are
both label-efficient and robust. We empirically evaluate the proposed
Adversarial Contrastive Learning (ACL) and show it can consistently outperform
existing methods. For example on the CIFAR-10 dataset, ACL outperforms the
previous state-of-the-art unsupervised robust pre-training approach by 2.99% on
robust accuracy and 2.14% on standard accuracy. We further demonstrate that ACL
pre-training can improve semi-supervised adversarial training, even when only a
few labeled examples are available. Our codes and pre-trained models have been
released at: https://github.com/VITA-Group/Adversarial-Contrastive-Learning.