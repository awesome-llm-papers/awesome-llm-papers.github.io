---
layout: publication
title: 'Universal Natural Language Processing With Limited Annotations: Try Few-shot
  Textual Entailment As A Start'
authors: Wenpeng Yin, Nazneen Fatema Rajani, Dragomir Radev, Richard Socher, Caiming
  Xiong
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: yin2020universal
citations: 64
additional_links: [{name: Code, url: 'https://github.com/salesforce/UniversalFewShotNLP'},
  {name: Paper, url: 'https://arxiv.org/abs/2010.02584'}]
tags: ["EMNLP", "Few-Shot"]
short_authors: Yin et al.
---
A standard way to address different NLP problems is by first constructing a
problem-specific dataset, then building a model to fit this dataset. To build
the ultimate artificial intelligence, we desire a single machine that can
handle diverse new problems, for which task-specific annotations are limited.
We bring up textual entailment as a unified solver for such NLP problems.
However, current research of textual entailment has not spilled much ink on the
following questions: (i) How well does a pretrained textual entailment system
generalize across domains with only a handful of domain-specific examples? and
(ii) When is it worth transforming an NLP task into textual entailment? We
argue that the transforming is unnecessary if we can obtain rich annotations
for this task. Textual entailment really matters particularly when the target
NLP task has insufficient annotations.
  Universal NLP can be probably achieved through different routines. In this
work, we introduce Universal Few-shot textual Entailment (UFO-Entail). We
demonstrate that this framework enables a pretrained entailment model to work
well on new entailment domains in a few-shot setting, and show its
effectiveness as a unified solver for several downstream NLP tasks such as
question answering and coreference resolution when the end-task annotations are
limited. Code: https://github.com/salesforce/UniversalFewShotNLP