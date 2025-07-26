---
layout: publication
title: On The Effectiveness Of Parameter-efficient Fine-tuning
authors: Zihao Fu, Haoran Yang, Anthony Man-cho So, Wai Lam, Lidong Bing, Nigel Collier
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2023
bibkey: fu2022effectiveness
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.15583'}]
tags: ["AAAI", "Fine-Tuning", "Training Techniques"]
short_authors: Fu et al.
---
Fine-tuning pre-trained models has been ubiquitously proven to be effective
in a wide range of NLP tasks. However, fine-tuning the whole model is parameter
inefficient as it always yields an entirely new model for each task. Currently,
many research works propose to only fine-tune a small portion of the parameters
while keeping most of the parameters shared across different tasks. These
methods achieve surprisingly good performance and are shown to be more stable
than their corresponding fully fine-tuned counterparts. However, such kind of
methods is still not well understood. Some natural questions arise: How does
the parameter sparsity lead to promising performance? Why is the model more
stable than the fully fine-tuned models? How to choose the tunable parameters?
In this paper, we first categorize the existing methods into random approaches,
rule-based approaches, and projection-based approaches based on how they choose
which parameters to tune. Then, we show that all of the methods are actually
sparse fine-tuned models and conduct a novel theoretical analysis of them. We
indicate that the sparsity is actually imposing a regularization on the
original model by controlling the upper bound of the stability. Such stability
leads to better generalization capability which has been empirically observed
in a lot of recent research works. Despite the effectiveness of sparsity
grounded by our theory, it still remains an open problem of how to choose the
tunable parameters. To better choose the tunable parameters, we propose a novel
Second-order Approximation Method (SAM) which approximates the original problem
with an analytically solvable optimization function. The tunable parameters are
determined by directly optimizing the approximation function. The experimental
results show that our proposed SAM model outperforms many strong baseline
models and it also verifies our theoretical analysis.