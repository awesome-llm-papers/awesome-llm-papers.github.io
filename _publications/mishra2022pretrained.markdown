---
layout: publication
title: Pretrained Transformers Do Not Always Improve Robustness
authors: Mishra Swaroop, Sachdeva Bhavdeep Singh, Baral Chitta
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2022
bibkey: mishra2022pretrained
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.07663'}]
tags: [Security, Model Architecture, ACL, Transformer, Datasets, Reinforcement Learning]
---
Pretrained Transformers (PT) have been shown to improve Out of Distribution
(OOD) robustness than traditional models such as Bag of Words (BOW), LSTMs,
Convolutional Neural Networks (CNN) powered by Word2Vec and Glove embeddings.
How does the robustness comparison hold in a real world setting where some part
of the dataset can be noisy? Do PT also provide more robust representation than
traditional models on exposure to noisy data? We perform a comparative study on
10 models and find an empirical evidence that PT provide less robust
representation than traditional models on exposure to noisy data. We
investigate further and augment PT with an adversarial filtering (AF) mechanism
that has been shown to improve OOD generalization. However, increase in
generalization does not necessarily increase robustness, as we find that noisy
data fools the AF method powered by PT.