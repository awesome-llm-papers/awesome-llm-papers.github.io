---
layout: publication
title: Exploring The Universal Vulnerability Of Prompt-based Learning Paradigm
authors: Lei Xu, Yangyi Chen, Ganqu Cui, Hongcheng Gao, Zhiyuan Liu
conference: Arxiv
year: 2022
citations: 21
bibkey: xu2022exploring
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.05239'}, {name: Code,
    url: 'https://github.com/leix28/prompt-universal-vulnerability'}]
tags: [Training Techniques, Pre-Training, Few-Shot, Fine-Tuning, Has Code, Security,
  Prompting]
---
Prompt-based learning paradigm bridges the gap between pre-training and
fine-tuning, and works effectively under the few-shot setting. However, we find
that this learning paradigm inherits the vulnerability from the pre-training
stage, where model predictions can be misled by inserting certain triggers into
the text. In this paper, we explore this universal vulnerability by either
injecting backdoor triggers or searching for adversarial triggers on
pre-trained language models using only plain text. In both scenarios, we
demonstrate that our triggers can totally control or severely decrease the
performance of prompt-based models fine-tuned on arbitrary downstream tasks,
reflecting the universal vulnerability of the prompt-based learning paradigm.
Further experiments show that adversarial triggers have good transferability
among language models. We also find conventional fine-tuning models are not
vulnerable to adversarial triggers constructed from pre-trained language
models. We conclude by proposing a potential solution to mitigate our attack
methods. Code and data are publicly available at
https://github.com/leix28/prompt-universal-vulnerability