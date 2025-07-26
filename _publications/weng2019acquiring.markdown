---
layout: publication
title: Acquiring Knowledge From Pre-trained Model To Neural Machine Translation
authors: Rongxiang Weng, Heng Yu, Shujian Huang, Shanbo Cheng, Weihua Luo
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: weng2019acquiring
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.01774'}]
tags: ["AAAI", "Fine-Tuning", "Model Architecture", "Tools", "Training Techniques"]
short_authors: Weng et al.
---
Pre-training and fine-tuning have achieved great success in the natural
language process field. The standard paradigm of exploiting them includes two
steps: first, pre-training a model, e.g. BERT, with a large scale unlabeled
monolingual data. Then, fine-tuning the pre-trained model with labeled data
from downstream tasks. However, in neural machine translation (NMT), we address
the problem that the training objective of the bilingual task is far different
from the monolingual pre-trained model. This gap leads that only using
fine-tuning in NMT can not fully utilize prior language knowledge. In this
paper, we propose an APT framework for acquiring knowledge from the pre-trained
model to NMT. The proposed approach includes two modules: 1). a dynamic fusion
mechanism to fuse task-specific features adapted from general knowledge into
NMT network, 2). a knowledge distillation paradigm to learn language knowledge
continuously during the NMT training process. The proposed approach could
integrate suitable knowledge from pre-trained models to improve the NMT.
Experimental results on WMT English to German, German to English and Chinese to
English machine translation tasks show that our model outperforms strong
baselines and the fine-tuning counterparts.