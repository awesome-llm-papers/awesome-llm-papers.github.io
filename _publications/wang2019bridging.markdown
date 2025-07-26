---
layout: publication
title: Bridging The Gap Between Pre-training And Fine-tuning For End-to-end Speech
  Translation
authors: Chengyi Wang, Yu Wu, Shujie Liu, Zhenglu Yang, Ming Zhou
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: wang2019bridging
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.07575'}]
tags: ["AAAI", "Fine-Tuning", "Training Techniques"]
short_authors: Wang et al.
---
End-to-end speech translation, a hot topic in recent years, aims to translate
a segment of audio into a specific language with an end-to-end model.
Conventional approaches employ multi-task learning and pre-training methods for
this task, but they suffer from the huge gap between pre-training and
fine-tuning. To address these issues, we propose a Tandem Connectionist
Encoding Network (TCEN) which bridges the gap by reusing all subnets in
fine-tuning, keeping the roles of subnets consistent, and pre-training the
attention module. Furthermore, we propose two simple but effective methods to
guarantee the speech encoder outputs and the MT encoder inputs are consistent
in terms of semantic representation and sequence length. Experimental results
show that our model outperforms baselines 2.2 BLEU on a large benchmark
dataset.