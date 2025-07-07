---
layout: publication
title: 'Generalization In Generation: A Closer Look At Exposure Bias'
authors: Florian Schmidt
conference: Arxiv
year: 2019
citations: 29
bibkey: schmidt2019generalization
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.00292'}]
tags: [Ethics and Bias, Training Techniques, GPT, Fine-Tuning, Tools, Reinforcement
    Learning, Agentic, Survey Paper, Language Modeling]
---
Exposure bias refers to the train-test discrepancy that seemingly arises when
an autoregressive generative model uses only ground-truth contexts at training
time but generated ones at test time. We separate the contributions of the
model and the learning framework to clarify the debate on consequences and
review proposed counter-measures. In this light, we argue that generalization
is the underlying property to address and propose unconditional generation as
its fundamental benchmark. Finally, we combine latent variable modeling with a
recent formulation of exploration in reinforcement learning to obtain a
rigorous handling of true and generated contexts. Results on language modeling
and variational sentence auto-encoding confirm the model's generalization
capability.