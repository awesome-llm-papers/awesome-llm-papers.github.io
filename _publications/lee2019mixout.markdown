---
layout: publication
title: 'Mixout: Effective Regularization To Finetune Large-scale Pretrained Language
  Models'
authors: Cheolhyoung Lee, Kyunghyun Cho, Wanmo Kang
conference: Arxiv
year: 2019
bibkey: lee2019mixout
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.11299'}]
tags: ["Training Techniques"]
short_authors: Cheolhyoung Lee, Kyunghyun Cho, Wanmo Kang
---
In natural language processing, it has been observed recently that
generalization could be greatly improved by finetuning a large-scale language
model pretrained on a large unlabeled corpus. Despite its recent success and
wide adoption, finetuning a large pretrained language model on a downstream
task is prone to degenerate performance when there are only a small number of
training instances available. In this paper, we introduce a new regularization
technique, to which we refer as "mixout", motivated by dropout. Mixout
stochastically mixes the parameters of two models. We show that our mixout
technique regularizes learning to minimize the deviation from one of the two
models and that the strength of regularization adapts along the optimization
trajectory. We empirically evaluate the proposed mixout and its variants on
finetuning a pretrained language model on downstream tasks. More specifically,
we demonstrate that the stability of finetuning and the average accuracy
greatly increase when we use the proposed approach to regularize finetuning of
BERT on downstream tasks in GLUE.