---
layout: publication
title: Experimental Design For Active Transductive Inference In Large Language Models
authors: Mukherjee et al.
conference: Proceedings of the 23rd international conference on Machine learning  -
  ICML '06
year: 2024
bibkey: mukherjee2024experimental
citations: 201
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.08846'}]
tags: [Training Techniques, Prompting, Evaluation, ICML, Few Shot]
---
One emergent ability of large language models (LLMs) is that query-specific
examples can be included in the prompt at inference time. In this work, we use
active learning for adaptive prompt design and call it Active In-context Prompt
Design (AIPD). We design the LLM prompt by adaptively choosing few-shot
examples from a training set to optimize performance on a test set. The
training examples are initially unlabeled and we obtain the label of the most
informative ones, which maximally reduces uncertainty in the LLM prediction. We
propose two algorithms, GO and SAL, which differ in how the few-shot examples
are chosen. We analyze these algorithms in linear models: first GO and then use
its equivalence with SAL. We experiment with many different tasks in small,
medium-sized, and large language models; and show that GO and SAL outperform
other methods for choosing few-shot examples in the LLM prompt at inference
time.