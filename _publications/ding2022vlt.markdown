---
layout: publication
title: 'VLT: Vision-language Transformer And Query Generation For Referring Segmentation'
authors: Henghui Ding, Chang Liu, Suchen Wang, Xudong Jiang
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2022
bibkey: ding2022vlt
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.15871'}]
tags: ["Model Architecture"]
short_authors: Ding et al.
---
We propose a Vision-Language Transformer (VLT) framework for referring
segmentation to facilitate deep interactions among multi-modal information and
enhance the holistic understanding to vision-language features. There are
different ways to understand the dynamic emphasis of a language expression,
especially when interacting with the image. However, the learned queries in
existing transformer works are fixed after training, which cannot cope with the
randomness and huge diversity of the language expressions. To address this
issue, we propose a Query Generation Module, which dynamically produces
multiple sets of input-specific queries to represent the diverse comprehensions
of language expression. To find the best among these diverse comprehensions, so
as to generate a better mask, we propose a Query Balance Module to selectively
fuse the corresponding responses of the set of queries. Furthermore, to enhance
the model's ability in dealing with diverse language expressions, we consider
inter-sample learning to explicitly endow the model with knowledge of
understanding different language expressions to the same object. We introduce
masked contrastive learning to narrow down the features of different
expressions for the same target object while distinguishing the features of
different objects. The proposed approach is lightweight and achieves new
state-of-the-art referring segmentation results consistently on five datasets.