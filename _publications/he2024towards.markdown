---
layout: publication
title: Towards Natural Machine Unlearning
authors: He et al.
conference: 2015 IEEE Symposium on Security and Privacy
year: 2024
bibkey: he2024towards
citations: 276
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.15495'}]
tags: [Security, Training Techniques, Fine Tuning, Privacy]
---
Machine unlearning (MU) aims to eliminate information that has been learned
from specific training data, namely forgetting data, from a pre-trained model.
Currently, the mainstream of existing MU methods involves modifying the
forgetting data with incorrect labels and subsequently fine-tuning the model.
While learning such incorrect information can indeed remove knowledge, the
process is quite unnatural as the unlearning process undesirably reinforces the
incorrect information and leads to over-forgetting. Towards more
\textit\{natural\} machine unlearning, we inject correct information from the
remaining data to the forgetting samples when changing their labels. Through
pairing these adjusted samples with their labels, the model will tend to use
the injected correct information and naturally suppress the information meant
to be forgotten. Albeit straightforward, such a first step towards natural
machine unlearning can significantly outperform current state-of-the-art
approaches. In particular, our method substantially reduces the over-forgetting
and leads to strong robustness to hyperparameters, making it a promising
candidate for practical machine unlearning.