---
layout: publication
title: Fine-tuning Language Models Via Epistemic Neural Networks
authors: Osband et al.
conference: Patterns
year: 2022
bibkey: osband2022fine
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.01568'}]
tags: [Fine Tuning, Model Architecture, Training Techniques, BERT]
---
Language models often pre-train on large unsupervised text corpora, then
fine-tune on additional task-specific data. However, typical fine-tuning
schemes do not prioritize the examples that they tune on. We show that, if you
can prioritize informative training data, you can achieve better performance
while using fewer labels. To do this we augment a language model with an
epinet: a small additional network that helps to estimate model uncertainty and
forms an \textit\{epistemic neural network\} (ENN). ENNs are neural networks that
can know what they don't know. Using an epinet to prioritize uncertain data, we
can fine-tune BERT on GLUE tasks to the same performance while using 2x less
data than training without prioritization. We also investigate performance in
synthetic neural network generative models designed to build understanding. In
each setting, using an epinet outperforms heuristic active learning schemes.