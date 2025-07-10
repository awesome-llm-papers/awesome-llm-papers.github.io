---
layout: publication
title: 'Noisytune: A Little Noise Can Help You Finetune Pretrained Language Models
  Better'
authors: Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang, Xing Xie
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2022
citations: 17
bibkey: wu2022little
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.12024'}]
tags: [Training Techniques, Fine-Tuning, Evaluation]
---
Effectively finetuning pretrained language models (PLMs) is critical for
their success in downstream tasks. However, PLMs may have risks in overfitting
the pretraining tasks and data, which usually have gap with the target
downstream tasks. Such gap may be difficult for existing PLM finetuning methods
to overcome and lead to suboptimal performance. In this paper, we propose a
very simple yet effective method named NoisyTune to help better finetune PLMs
on downstream tasks by adding some noise to the parameters of PLMs before
fine-tuning. More specifically, we propose a matrix-wise perturbing method
which adds different uniform noises to different parameter matrices based on
their standard deviations. In this way, the varied characteristics of different
types of parameters in PLMs can be considered. Extensive experiments on both
GLUE English benchmark and XTREME multilingual benchmark show NoisyTune can
consistently empower the finetuning of different PLMs on different downstream
tasks.