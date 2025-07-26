---
layout: publication
title: Industry Scale Semi-supervised Learning For Natural Language Understanding
authors: Luoxin Chen, Francisco Garcia, Varun Kumar, He Xie, Jianhua Lu
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies: Industry
  Papers'
year: 2021
bibkey: chen2021industry
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.15871'}]
tags: ["NAACL", "Training Techniques"]
short_authors: Chen et al.
---
This paper presents a production Semi-Supervised Learning (SSL) pipeline
based on the student-teacher framework, which leverages millions of unlabeled
examples to improve Natural Language Understanding (NLU) tasks. We investigate
two questions related to the use of unlabeled data in production SSL context:
1) how to select samples from a huge unlabeled data pool that are beneficial
for SSL training, and 2) how do the selected data affect the performance of
different state-of-the-art SSL techniques. We compare four widely used SSL
techniques, Pseudo-Label (PL), Knowledge Distillation (KD), Virtual Adversarial
Training (VAT) and Cross-View Training (CVT) in conjunction with two data
selection methods including committee-based selection and submodular
optimization based selection. We further examine the benefits and drawbacks of
these techniques when applied to intent classification (IC) and named entity
recognition (NER) tasks, and provide guidelines specifying when each of these
methods might be beneficial to improve large scale NLU systems.