---
layout: publication
title: 'Domain Adaptation And Multi-domain Adaptation For Neural Machine Translation:
  A Survey'
authors: Saunders Danielle
conference: Journal of Artificial Intelligence Research
year: 2021
bibkey: saunders2021domain
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.06951'}]
tags: [Training Techniques, Model Architecture, Survey Paper, Reinforcement Learning,
  Fine Tuning]
---
The development of deep learning techniques has allowed Neural Machine
Translation (NMT) models to become extremely powerful, given sufficient
training data and training time. However, systems struggle when translating
text from a new domain with a distinct style or vocabulary. Fine-tuning on
in-domain data allows good domain adaptation, but requires sufficient relevant
bilingual data. Even if this is available, simple fine-tuning can cause
overfitting to new data and `catastrophic forgetting' of previously learned
behaviour.
  We concentrate on robust approaches to domain adaptation for NMT,
particularly where a system may need to translate across multiple domains. We
divide techniques into those revolving around data selection or generation,
model architecture, parameter adaptation procedure, and inference procedure. We
finally highlight the benefits of domain adaptation and multi-domain adaptation
techniques to other lines of NMT research.