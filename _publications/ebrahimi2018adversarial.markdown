---
layout: publication
title: On Adversarial Examples For Character-level Neural Machine Translation
authors: Javid Ebrahimi, Daniel Lowd, Dejing Dou
conference: COLING 2018
year: 2018
bibkey: ebrahimi2018adversarial
citations: 155
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.09030'}]
tags: ["COLING"]
short_authors: Javid Ebrahimi, Daniel Lowd, Dejing Dou
---
Evaluating on adversarial examples has become a standard procedure to measure
robustness of deep learning models. Due to the difficulty of creating white-box
adversarial examples for discrete text input, most analyses of the robustness
of NLP models have been done through black-box adversarial examples. We
investigate adversarial examples for character-level neural machine translation
(NMT), and contrast black-box adversaries with a novel white-box adversary,
which employs differentiable string-edit operations to rank adversarial
changes. We propose two novel types of attacks which aim to remove or change a
word in a translation, rather than simply break the NMT. We demonstrate that
white-box adversarial examples are significantly stronger than their black-box
counterparts in different attack scenarios, which show more serious
vulnerabilities than previously known. In addition, after performing
adversarial training, which takes only 3 times longer than regular training, we
can improve the model's robustness significantly.