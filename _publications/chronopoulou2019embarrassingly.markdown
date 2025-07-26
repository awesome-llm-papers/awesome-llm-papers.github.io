---
layout: publication
title: An Embarrassingly Simple Approach For Transfer Learning From Pretrained Language
  Models
authors: Alexandra Chronopoulou, Christos Baziotis, Alexandros Potamianos
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: chronopoulou2019embarrassingly
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.10547'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Alexandra Chronopoulou, Christos Baziotis, Alexandros Potamianos
---
A growing number of state-of-the-art transfer learning methods employ
language models pretrained on large generic corpora. In this paper we present a
conceptually simple and effective transfer learning approach that addresses the
problem of catastrophic forgetting. Specifically, we combine the task-specific
optimization function with an auxiliary language model objective, which is
adjusted during the training process. This preserves language regularities
captured by language models, while enabling sufficient adaptation for solving
the target task. Our method does not require pretraining or finetuning separate
components of the network and we train our models end-to-end in a single step.
We present results on a variety of challenging affective and text
classification tasks, surpassing well established transfer learning methods
with greater level of complexity.