---
layout: publication
title: 'GLM: General Language Model Pretraining With Autoregressive Blank Infilling'
authors: Zhengxiao Du, Yujie Qian, Xiao Liu, Ming Ding, Jiezhong Qiu, Zhilin Yang,
  Jie Tang
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: du2021glm
citations: 561
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.10360'}]
tags: ["Model Architecture"]
short_authors: Du et al.
---
There have been various types of pretraining architectures including
autoencoding models (e.g., BERT), autoregressive models (e.g., GPT), and
encoder-decoder models (e.g., T5). However, none of the pretraining frameworks
performs the best for all tasks of three main categories including natural
language understanding (NLU), unconditional generation, and conditional
generation. We propose a General Language Model (GLM) based on autoregressive
blank infilling to address this challenge. GLM improves blank filling
pretraining by adding 2D positional encodings and allowing an arbitrary order
to predict spans, which results in performance gains over BERT and T5 on NLU
tasks. Meanwhile, GLM can be pretrained for different types of tasks by varying
the number and lengths of blanks. On a wide range of tasks across NLU,
conditional and unconditional generation, GLM outperforms BERT, T5, and GPT
given the same model sizes and data, and achieves the best performance from a
single pretrained model with 1.25x parameters of BERT Large , demonstrating its
generalizability to different downstream tasks.