---
layout: publication
title: 'Minilmv2: Multi-head Self-attention Relation Distillation For Compressing
  Pretrained Transformers'
authors: Wenhui Wang, Hangbo Bao, Shaohan Huang, Li Dong, Furu Wei
conference: 'Findings of the Association for Computational Linguistics: ACL-IJCNLP
  2021'
year: 2021
bibkey: wang2020minilmv2
citations: 184
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15828'}]
tags: ["Model Architecture"]
short_authors: Wang et al.
---
We generalize deep self-attention distillation in MiniLM (Wang et al., 2020)
by only using self-attention relation distillation for task-agnostic
compression of pretrained Transformers. In particular, we define multi-head
self-attention relations as scaled dot-product between the pairs of query, key,
and value vectors within each self-attention module. Then we employ the above
relational knowledge to train the student model. Besides its simplicity and
unified principle, more favorably, there is no restriction in terms of the
number of student's attention heads, while most previous work has to guarantee
the same head number between teacher and student. Moreover, the fine-grained
self-attention relations tend to fully exploit the interaction knowledge
learned by Transformer. In addition, we thoroughly examine the layer selection
strategy for teacher models, rather than just relying on the last layer as in
MiniLM. We conduct extensive experiments on compressing both monolingual and
multilingual pretrained models. Experimental results demonstrate that our
models distilled from base-size and large-size teachers (BERT, RoBERTa and
XLM-R) outperform the state-of-the-art.