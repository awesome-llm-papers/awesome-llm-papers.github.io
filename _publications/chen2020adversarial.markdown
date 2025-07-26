---
layout: publication
title: 'Adversarial Robustness: From Self-supervised Pre-training To Fine-tuning'
authors: Tianlong Chen, Sijia Liu, Shiyu Chang, Yu Cheng, Lisa Amini, Zhangyang Wang
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: chen2020adversarial
citations: 156
additional_links: [{name: Code, url: 'https://github.com/TAMU-VITA/Adv-SS-Pretraining'},
  {name: Paper, url: 'https://arxiv.org/abs/2003.12862'}]
tags: ["CVPR", "Fine-Tuning", "Security", "Training Techniques"]
short_authors: Chen et al.
---
Pretrained models from self-supervision are prevalently used in fine-tuning
downstream tasks faster or for better accuracy. However, gaining robustness
from pretraining is left unexplored. We introduce adversarial training into
self-supervision, to provide general-purpose robust pre-trained models for the
first time. We find these robust pre-trained models can benefit the subsequent
fine-tuning in two ways: i) boosting final model robustness; ii) saving the
computation cost, if proceeding towards adversarial fine-tuning. We conduct
extensive experiments to demonstrate that the proposed framework achieves large
performance margins (eg, 3.83% on robust accuracy and 1.3% on standard
accuracy, on the CIFAR-10 dataset), compared with the conventional end-to-end
adversarial training baseline. Moreover, we find that different self-supervised
pre-trained models have a diverse adversarial vulnerability. It inspires us to
ensemble several pretraining tasks, which boosts robustness more. Our ensemble
strategy contributes to a further improvement of 3.59% on robust accuracy,
while maintaining a slightly higher standard accuracy on CIFAR-10. Our codes
are available at https://github.com/TAMU-VITA/Adv-SS-Pretraining.