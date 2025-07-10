---
layout: publication
title: Mitigating Political Bias In Language Models Through Reinforced Calibration
authors: Ruibo Liu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
citations: 24
bibkey: liu2021mitigating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.14795'}]
tags: [Model Architecture, Ethics and Bias, GPT, Tools, Reinforcement Learning, Training
    Techniques, Evaluation]
---
Current large-scale language models can be politically biased as a result of
the data they are trained on, potentially causing serious problems when they
are deployed in real-world settings. In this paper, we describe metrics for
measuring political bias in GPT-2 generation and propose a reinforcement
learning (RL) framework for mitigating political biases in generated text. By
using rewards from word embeddings or a classifier, our RL framework guides
debiased generation without having access to the training data or requiring the
model to be retrained. In empirical experiments on three attributes sensitive
to political bias (gender, location, and topic), our methods reduced bias
according to both our metrics and human evaluation, while maintaining
readability and semantic coherence.