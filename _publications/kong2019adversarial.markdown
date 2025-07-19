---
layout: publication
title: An Adversarial Approach To High-quality, Sentiment-controlled Neural Dialogue
  Generation
authors: Kong et al.
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2019
bibkey: kong2019adversarial
citations: 356
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.07129'}]
tags: [Security, Tools, Training Techniques, Evaluation, EMNLP]
---
In this work, we propose a method for neural dialogue response generation
that allows not only generating semantically reasonable responses according to
the dialogue history, but also explicitly controlling the sentiment of the
response via sentiment labels. Our proposed model is based on the paradigm of
conditional adversarial learning; the training of a sentiment-controlled
dialogue generator is assisted by an adversarial discriminator which assesses
the fluency and feasibility of the response generating from the dialogue
history and a given sentiment label. Because of the flexibility of our
framework, the generator could be a standard sequence-to-sequence (SEQ2SEQ)
model or a more complicated one such as a conditional variational
autoencoder-based SEQ2SEQ model. Experimental results using automatic and human
evaluation both demonstrate that our proposed framework is able to generate
both semantically reasonable and sentiment-controlled dialogue responses.