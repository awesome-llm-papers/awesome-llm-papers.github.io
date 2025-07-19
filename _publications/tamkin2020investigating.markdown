---
layout: publication
title: Investigating Transferability In Pretrained Language Models
authors: Tamkin et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: tamkin2020investigating
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14975'}]
tags: [Model Architecture, Fine Tuning, Training Techniques, BERT, ACL, EMNLP, Datasets]
---
How does language model pretraining help transfer learning? We consider a
simple ablation technique for determining the impact of each pretrained layer
on transfer task performance. This method, partial reinitialization, involves
replacing different layers of a pretrained model with random weights, then
finetuning the entire model on the transfer task and observing the change in
performance. This technique reveals that in BERT, layers with high probing
performance on downstream GLUE tasks are neither necessary nor sufficient for
high accuracy on those tasks. Furthermore, the benefit of using pretrained
parameters for a layer varies dramatically with finetuning dataset size:
parameters that provide tremendous performance improvement when data is
plentiful may provide negligible benefits in data-scarce settings. These
results reveal the complexity of the transfer learning process, highlighting
the limitations of methods that operate on frozen models or single data
samples.