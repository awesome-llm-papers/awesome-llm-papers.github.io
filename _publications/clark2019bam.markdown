---
layout: publication
title: BAM! Born-again Multi-task Networks For Natural Language Understanding
authors: Clark et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: clark2019bam
citations: 221
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.04829'}]
tags: [Model Architecture, Distillation, Training Techniques, Efficiency And Optimization,
  Fine Tuning, BERT, Evaluation, ACL, Datasets]
---
It can be challenging to train multi-task neural networks that outperform or
even match their single-task counterparts. To help address this, we propose
using knowledge distillation where single-task models teach a multi-task model.
We enhance this training with teacher annealing, a novel method that gradually
transitions the model from distillation to supervised learning, helping the
multi-task model surpass its single-task teachers. We evaluate our approach by
multi-task fine-tuning BERT on the GLUE benchmark. Our method consistently
improves over standard single-task and multi-task training.