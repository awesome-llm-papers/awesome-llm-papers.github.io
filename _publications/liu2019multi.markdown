---
layout: publication
title: Multi-task Deep Neural Networks For Natural Language Understanding
authors: Xiaodong Liu, Pengcheng He, Weizhu Chen, Jianfeng Gao
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: liu2019multi
citations: 1049
additional_links: [{name: Code, url: 'https://github.com/namisan/mt-dnn'}, {name: Paper,
    url: 'https://arxiv.org/abs/1901.11504'}]
tags: ["Model Architecture"]
short_authors: Liu et al.
---
In this paper, we present a Multi-Task Deep Neural Network (MT-DNN) for
learning representations across multiple natural language understanding (NLU)
tasks. MT-DNN not only leverages large amounts of cross-task data, but also
benefits from a regularization effect that leads to more general
representations in order to adapt to new tasks and domains. MT-DNN extends the
model proposed in Liu et al. (2015) by incorporating a pre-trained
bidirectional transformer language model, known as BERT (Devlin et al., 2018).
MT-DNN obtains new state-of-the-art results on ten NLU tasks, including SNLI,
SciTail, and eight out of nine GLUE tasks, pushing the GLUE benchmark to 82.7%
(2.2% absolute improvement). We also demonstrate using the SNLI and SciTail
datasets that the representations learned by MT-DNN allow domain adaptation
with substantially fewer in-domain labels than the pre-trained BERT
representations. The code and pre-trained models are publicly available at
https://github.com/namisan/mt-dnn.