---
layout: publication
title: 'KRISP: Integrating Implicit And Symbolic Knowledge For Open-domain Knowledge-based
  VQA'
authors: Kenneth Marino, Xinlei Chen, Devi Parikh, Abhinav Gupta, Marcus Rohrbach
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: marino2020krisp
citations: 126
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.11014'}]
tags: ["CVPR"]
short_authors: Marino et al.
---
One of the most challenging question types in VQA is when answering the
question requires outside knowledge not present in the image. In this work we
study open-domain knowledge, the setting when the knowledge required to answer
a question is not given/annotated, neither at training nor test time. We tap
into two types of knowledge representations and reasoning. First, implicit
knowledge which can be learned effectively from unsupervised language
pre-training and supervised training data with transformer-based models.
Second, explicit, symbolic knowledge encoded in knowledge bases. Our approach
combines both - exploiting the powerful implicit reasoning of transformer
models for answer prediction, and integrating symbolic representations from a
knowledge graph, while never losing their explicit semantics to an implicit
embedding. We combine diverse sources of knowledge to cover the wide variety of
knowledge needed to solve knowledge-based questions. We show our approach,
KRISP (Knowledge Reasoning with Implicit and Symbolic rePresentations),
significantly outperforms state-of-the-art on OK-VQA, the largest available
dataset for open-domain knowledge-based VQA. We show with extensive ablations
that while our model successfully exploits implicit knowledge reasoning, the
symbolic answer module which explicitly connects the knowledge graph to the
answer vocabulary is critical to the performance of our method and generalizes
to rare answers.