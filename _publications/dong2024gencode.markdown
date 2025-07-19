---
layout: publication
title: 'Gencode: A Generic Data Augmentation Framework For Boosting Deep Learning-based
  Code Understanding'
authors: Dong et al.
conference: 2018 IEEE Symposium Series on Computational Intelligence (SSCI)
year: 2024
bibkey: dong2024gencode
citations: 469
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.15769'}]
tags: [RAG, Training Techniques, Tools, Evaluation, Security, LLM For Code]
---
Pre-trained code models lead the era of code intelligence with multiple
models have been designed with impressive performance. However, one important
problem, data augmentation for code data that automatically helps developers
prepare training data lacks study in this field. In this paper, we introduce a
generic data augmentation framework, GenCode, to enhance the training of code
understanding models. Simply speaking, GenCode follows a
generation-and-selection paradigm to prepare useful training code data.
Specifically, it employs code transformation techniques to generate new code
candidates first and then selects important ones as the training data by
importance metrics. To evaluate the effectiveness of GenCode, we conduct
experiments on four code understanding tasks (e.g., code clone detection) and
three pre-trained code models (e.g., CodeT5). Compared to the state-of-the-art
(SOTA) code augmentation method, MixCode, GenCode produces code models with
2.92% higher accuracy and 4.90% robustness on average.