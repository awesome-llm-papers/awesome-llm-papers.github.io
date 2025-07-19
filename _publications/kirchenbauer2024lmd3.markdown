---
layout: publication
title: 'LMD3: Language Model Data Density Dependence'
authors: Kirchenbauer et al.
conference: Proceedings of the 27th annual international ACM SIGIR conference on Research
  and development in information retrieval
year: 2024
bibkey: kirchenbauer2024lmd3
citations: 143
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.06331'}]
tags: [Tools, Training Techniques, Reinforcement Learning, SIGIR]
---
We develop a methodology for analyzing language model task performance at the
individual example level based on training data density estimation. Experiments
with paraphrasing as a controlled intervention on finetuning data demonstrate
that increasing the support in the training distribution for specific test
queries results in a measurable increase in density, which is also a
significant predictor of the performance increase caused by the intervention.
Experiments with pretraining data demonstrate that we can explain a significant
fraction of the variance in model perplexity via density measurements. We
conclude that our framework can provide statistical evidence of the dependence
of a target model's predictions on subsets of its training data, and can more
generally be used to characterize the support (or lack thereof) in the training
data for a given test task.