---
layout: publication
title: 'Towards Efficient Fine-tuning Of Pre-trained Code Models: An Experimental
  Study And Beyond'
authors: Ensheng Shi et al.
conference: 'ISSTA ''23: 32nd ACM SIGSOFT International Symposium on Software Testing
  and Analysis'
year: 2023
citations: 18
bibkey: shi2023towards
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.05216'}, {name: Code,
    url: 'https://github.com/DeepSoftwareAnalytics/Telly'}]
tags: [Has Code, Model Architecture, Fine-Tuning, Training Techniques, BERT]
---
Recently, fine-tuning pre-trained code models such as CodeBERT on downstream
tasks has achieved great success in many software testing and analysis tasks.
While effective and prevalent, fine-tuning the pre-trained parameters incurs a
large computational cost. In this paper, we conduct an extensive experimental
study to explore what happens to layer-wise pre-trained representations and
their encoded code knowledge during fine-tuning. We then propose efficient
alternatives to fine-tune the large pre-trained code model based on the above
findings. Our experimental study shows that (1) lexical, syntactic and
structural properties of source code are encoded in the lower, intermediate,
and higher layers, respectively, while the semantic property spans across the
entire model. (2) The process of fine-tuning preserves most of the code
properties. Specifically, the basic code properties captured by lower and
intermediate layers are still preserved during fine-tuning. Furthermore, we
find that only the representations of the top two layers change most during
fine-tuning for various downstream tasks. (3) Based on the above findings, we
propose Telly to efficiently fine-tune pre-trained code models via layer
freezing. The extensive experimental results on five various downstream tasks
demonstrate that training parameters and the corresponding time cost are
greatly reduced, while performances are similar or better. Replication package
including source code, datasets, and online Appendix is available at:
https://github.com/DeepSoftwareAnalytics/Telly.