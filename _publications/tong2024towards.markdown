---
layout: publication
title: Towards Resource Efficient And Interpretable Bias Mitigation In Large Language
  Models
authors: Tong et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: tong2024towards
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.01711'}]
tags: [Interpretability And Explainability, RAG, EMNLP, Training Techniques, Alt,
  Bias Mitigation, Evaluation, Ethics And Bias, Efficiency And Optimization, Applications]
---
Although large language models (LLMs) have demonstrated their effectiveness
in a wide range of applications, they have also been observed to perpetuate
unwanted biases present in the training data, potentially leading to harm for
marginalized communities. In this paper, we mitigate bias by leveraging small
biased and anti-biased expert models to obtain a debiasing signal that will be
added to the LLM output at decoding-time. This approach combines resource
efficiency with interpretability and can be optimized for mitigating specific
types of bias, depending on the target use case. Experiments on mitigating
gender, race, and religion biases show a reduction in bias on several local and
global bias metrics while preserving language model performance.