---
layout: publication
title: Improving Gender Fairness Of Pre-trained Language Models Without Catastrophic
  Forgetting
authors: Zahra Fatemi, Chen Xing, Wenhao Liu, Caiming Xiong
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2021
citations: 15
bibkey: fatemi2021improving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.05367'}]
tags: [Ethics and Bias, Fairness, Bias Mitigation, Prompting, Pre-Training, Training
    Techniques]
---
Existing studies addressing gender bias of pre-trained language models,
usually build a small gender-neutral data set and conduct a second phase
pre-training on the model with such data. However, given the limited size and
concentrated focus of the gender-neutral data, catastrophic forgetting would
occur during second-phase pre-training. Forgetting information in the original
training data may damage the model's downstream performance by a large margin.
In this work, we empirically show that catastrophic forgetting occurs in such
methods by evaluating them with general NLP tasks in GLUE. Then, we propose a
new method, GEnder Equality Prompt (GEEP), to improve gender fairness of
pre-trained models with less forgetting. GEEP freezes the pre-trained model and
learns gender-related prompts with gender-neutral data. Empirical results show
that GEEP not only achieves SOTA performances on gender fairness tasks, but
also forgets less and performs better on GLUE by a large margin.