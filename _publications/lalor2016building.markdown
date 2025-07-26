---
layout: publication
title: Building An Evaluation Scale Using Item Response Theory
authors: John P. Lalor, Hao Wu, Hong Yu
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: lalor2016building
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.08889'}]
tags: ["EMNLP", "Evaluation"]
short_authors: John P. Lalor, Hao Wu, Hong Yu
---
Evaluation of NLP methods requires testing against a previously vetted
gold-standard test set and reporting standard metrics
(accuracy/precision/recall/F1). The current assumption is that all items in a
given test set are equal with regards to difficulty and discriminating power.
We propose Item Response Theory (IRT) from psychometrics as an alternative
means for gold-standard test-set generation and NLP system evaluation. IRT is
able to describe characteristics of individual items - their difficulty and
discriminating power - and can account for these characteristics in its
estimation of human intelligence or ability for an NLP task. In this paper, we
demonstrate IRT by generating a gold-standard test set for Recognizing Textual
Entailment. By collecting a large number of human responses and fitting our IRT
model, we show that our IRT model compares NLP systems with the performance in
a human population and is able to provide more insight into system performance
than standard evaluation metrics. We show that a high accuracy score does not
always imply a high IRT score, which depends on the item characteristics and
the response pattern.