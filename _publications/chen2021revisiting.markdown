---
layout: publication
title: Revisiting Self-training For Few-shot Learning Of Language Model
authors: Yiming Chen et al.
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
citations: 17
bibkey: chen2021revisiting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.01256'}]
tags: [Security, Fine-Tuning, Few-Shot, Prompting, Training Techniques, Evaluation]
---
As unlabeled data carry rich task-relevant information, they are proven
useful for few-shot learning of language model. The question is how to
effectively make use of such data. In this work, we revisit the self-training
technique for language model fine-tuning and present a state-of-the-art
prompt-based few-shot learner, SFLM. Given two views of a text sample via weak
and strong augmentation techniques, SFLM generates a pseudo label on the weakly
augmented version. Then, the model predicts the same pseudo label when
fine-tuned with the strongly augmented version. This simple approach is shown
to outperform other state-of-the-art supervised and semi-supervised
counterparts on six sentence classification and six sentence-pair
classification benchmarking tasks. In addition, SFLM only relies on a few
in-domain unlabeled data. We conduct a comprehensive analysis to demonstrate
the robustness of our proposed approach under various settings, including
augmentation techniques, model scale, and few-shot knowledge transfer across
tasks.