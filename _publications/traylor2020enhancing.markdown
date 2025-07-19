---
layout: publication
title: Enhancing Review Comprehension With Domain-specific Commonsense
authors: Traylor et al.
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2020
bibkey: traylor2020enhancing
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.03020'}]
tags: [Model Architecture, Distillation, Efficiency And Optimization, BERT, Evaluation,
  ACL, Applications, RAG, Datasets]
---
Review comprehension has played an increasingly important role in improving
the quality of online services and products and commonsense knowledge can
further enhance review comprehension. However, existing general-purpose
commonsense knowledge bases lack sufficient coverage and precision to
meaningfully improve the comprehension of domain-specific reviews. In this
paper, we introduce xSense, an effective system for review comprehension using
domain-specific commonsense knowledge bases (xSense KBs). We show that xSense
KBs can be constructed inexpensively and present a knowledge distillation
method that enables us to use xSense KBs along with BERT to boost the
performance of various review comprehension tasks. We evaluate xSense over
three review comprehension tasks: aspect extraction, aspect sentiment
classification, and question answering. We find that xSense outperforms the
state-of-the-art models for the first two tasks and improves the baseline BERT
QA model significantly, demonstrating the usefulness of incorporating
commonsense into review comprehension pipelines. To facilitate future research
and applications, we publicly release three domain-specific knowledge bases and
a domain-specific question answering benchmark along with this paper.