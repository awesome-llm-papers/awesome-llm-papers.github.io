---
layout: publication
title: Imitation Attacks And Defenses For Black-box Machine Translation Systems
authors: Wallace Eric, Stern Mitchell, Song Dawn
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: wallace2020imitation
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.15015'}]
tags: [RAG, EMNLP, Training Techniques, Model Architecture, Efficiency And Optimization,
  Security]
---
Adversaries may look to steal or attack black-box NLP systems, either for
financial gain or to exploit model errors. One setting of particular interest
is machine translation (MT), where models have high commercial value and errors
can be costly. We investigate possible exploits of black-box MT systems and
explore a preliminary defense against such threats. We first show that MT
systems can be stolen by querying them with monolingual sentences and training
models to imitate their outputs. Using simulated experiments, we demonstrate
that MT model stealing is possible even when imitation models have different
input data or architectures than their target models. Applying these ideas, we
train imitation models that reach within 0.6 BLEU of three production MT
systems on both high-resource and low-resource language pairs. We then leverage
the similarity of our imitation models to transfer adversarial examples to the
production systems. We use gradient-based attacks that expose inputs which lead
to semantically-incorrect translations, dropped content, and vulgar model
outputs. To mitigate these vulnerabilities, we propose a defense that modifies
translation outputs in order to misdirect the optimization of imitation models.
This defense degrades the adversary's BLEU score and attack success rate at
some cost in the defender's BLEU and inference speed.