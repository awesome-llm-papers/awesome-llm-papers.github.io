---
layout: publication
title: Toward Inference-optimal Mixture-of-expert Large Language Models
authors: Yun et al.
conference: Nature Medicine
year: 2024
bibkey: yun2024toward
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.02852'}]
tags: [Training Techniques, Transformer, Model Architecture, Efficiency And Optimization,
  Datasets]
---
Mixture-of-Expert (MoE) based large language models (LLMs), such as the
recent Mixtral and DeepSeek-MoE, have shown great promise in scaling model size
without suffering from the quadratic growth of training cost of dense
transformers. Like dense models, training MoEs requires answering the same
question: given a training budget, what is the optimal allocation on the model
size and number of tokens? We study the scaling law of MoE-based LLMs regarding
the relations between the model performance, model size, dataset size, and the
expert degree. Echoing previous research studying MoE in different contexts, we
observe the diminishing return of increasing the number of experts, but this
seems to suggest we should scale the number of experts until saturation, as the
training cost would remain constant, which is problematic during inference
time. We propose to amend the scaling law of MoE by introducing inference
efficiency as another metric besides the validation loss. We find that MoEs
with a few (4/8) experts are the most serving efficient solution under the same
performance, but costs 2.5-3.5x more in training. On the other hand, training a
(16/32) expert MoE much smaller (70-85%) than the loss-optimal solution, but
with a larger training dataset is a promising setup under a training budget.