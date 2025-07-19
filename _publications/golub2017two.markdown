---
layout: publication
title: Two-stage Synthesis Networks For Transfer Learning In Machine Comprehension
authors: Golub et al.
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: golub2017two
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.09789'}]
tags: [Datasets, EMNLP, Fine Tuning]
---
We develop a technique for transfer learning in machine comprehension (MC)
using a novel two-stage synthesis network (SynNet). Given a high-performing MC
model in one domain, our technique aims to answer questions about documents in
another domain, where we use no labeled data of question-answer pairs. Using
the proposed SynNet with a pretrained model from the SQuAD dataset on the
challenging NewsQA dataset, we achieve an F1 measure of 44.3% with a single
model and 46.6% with an ensemble, approaching performance of in-domain models
(F1 measure of 50.0%) and outperforming the out-of-domain baseline of 7.6%,
without use of provided annotations.