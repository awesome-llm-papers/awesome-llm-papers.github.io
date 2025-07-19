---
layout: publication
title: Training Data Leakage Analysis In Language Models
authors: Inan et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2021
bibkey: inan2021training
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.05405'}]
tags: [Model Architecture, Tools, Training Techniques, Evaluation, ACL, Applications,
  RAG, Transformer]
---
Recent advances in neural network based language models lead to successful
deployments of such models, improving user experience in various applications.
It has been demonstrated that strong performance of language models comes along
with the ability to memorize rare training samples, which poses serious privacy
threats in case the model is trained on confidential user content. In this
work, we introduce a methodology that investigates identifying the user content
in the training data that could be leaked under a strong and realistic threat
model. We propose two metrics to quantify user-level data leakage by measuring
a model's ability to produce unique sentence fragments within training data.
Our metrics further enable comparing different models trained on the same data
in terms of privacy. We demonstrate our approach through extensive numerical
studies on both RNN and Transformer based models. We further illustrate how the
proposed metrics can be utilized to investigate the efficacy of mitigations
like differentially private training or API hardening.