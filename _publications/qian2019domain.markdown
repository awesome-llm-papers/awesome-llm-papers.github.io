---
layout: publication
title: Domain Adaptive Dialog Generation Via Meta Learning
authors: Kun Qian, Zhou Yu
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: qian2019domain
citations: 138
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.03520'}]
tags: ["Datasets", "Fine-Tuning", "Training Techniques"]
short_authors: Kun Qian, Zhou Yu
---
Domain adaptation is an essential task in dialog system building because
there are so many new dialog tasks created for different needs every day.
Collecting and annotating training data for these new tasks is costly since it
involves real user interactions. We propose a domain adaptive dialog generation
method based on meta-learning (DAML). DAML is an end-to-end trainable dialog
system model that learns from multiple rich-resource tasks and then adapts to
new domains with minimal training samples. We train a dialog system model using
multiple rich-resource single-domain dialog data by applying the model-agnostic
meta-learning algorithm to dialog domain. The model is capable of learning a
competitive dialog system on a new domain with only a few training examples in
an efficient manner. The two-step gradient updates in DAML enable the model to
learn general features across multiple tasks. We evaluate our method on a
simulated dialog dataset and achieve state-of-the-art performance, which is
generalizable to new tasks.