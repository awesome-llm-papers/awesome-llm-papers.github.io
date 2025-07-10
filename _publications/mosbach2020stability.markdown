---
layout: publication
title: 'On The Stability Of Fine-tuning BERT: Misconceptions, Explanations, And Strong
  Baselines'
authors: Marius Mosbach, Maksym Andriushchenko, Dietrich Klakow
conference: Arxiv
year: 2020
citations: 199
bibkey: mosbach2020stability
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.04884'}, {name: Code,
    url: 'https://github.com/uds-lsv/bert-stable-fine-tuning'}]
tags: [Has Code, Model Architecture, Transformer, Fine-Tuning, Interpretability and
    Explainability, BERT, Efficiency and Optimization, Training Techniques, Evaluation]
---
Fine-tuning pre-trained transformer-based language models such as BERT has
become a common practice dominating leaderboards across various NLP benchmarks.
Despite the strong empirical performance of fine-tuned models, fine-tuning is
an unstable process: training the same model with multiple random seeds can
result in a large variance of the task performance. Previous literature (Devlin
et al., 2019; Lee et al., 2020; Dodge et al., 2020) identified two potential
reasons for the observed instability: catastrophic forgetting and small size of
the fine-tuning datasets. In this paper, we show that both hypotheses fail to
explain the fine-tuning instability. We analyze BERT, RoBERTa, and ALBERT,
fine-tuned on commonly used datasets from the GLUE benchmark, and show that the
observed instability is caused by optimization difficulties that lead to
vanishing gradients. Additionally, we show that the remaining variance of the
downstream task performance can be attributed to differences in generalization
where fine-tuned models with the same training loss exhibit noticeably
different test performance. Based on our analysis, we present a simple but
strong baseline that makes fine-tuning BERT-based models significantly more
stable than the previously proposed approaches. Code to reproduce our results
is available online: https://github.com/uds-lsv/bert-stable-fine-tuning.