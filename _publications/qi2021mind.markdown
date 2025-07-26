---
layout: publication
title: Mind The Style Of Text! Adversarial And Backdoor Attacks Based On Text Style
  Transfer
authors: Fanchao Qi, Yangyi Chen, Xurui Zhang, Mukai Li, Zhiyuan Liu, Maosong Sun
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: qi2021mind
citations: 74
additional_links: [{name: Code, url: 'https://github.com/thunlp/StyleAttack'}, {name: Paper,
    url: 'https://arxiv.org/abs/2110.07139'}]
tags: ["EMNLP", "Security"]
short_authors: Qi et al.
---
Adversarial attacks and backdoor attacks are two common security threats that
hang over deep learning. Both of them harness task-irrelevant features of data
in their implementation. Text style is a feature that is naturally irrelevant
to most NLP tasks, and thus suitable for adversarial and backdoor attacks. In
this paper, we make the first attempt to conduct adversarial and backdoor
attacks based on text style transfer, which is aimed at altering the style of a
sentence while preserving its meaning. We design an adversarial attack method
and a backdoor attack method, and conduct extensive experiments to evaluate
them. Experimental results show that popular NLP models are vulnerable to both
adversarial and backdoor attacks based on text style transfer -- the attack
success rates can exceed 90% without much effort. It reflects the limited
ability of NLP models to handle the feature of text style that has not been
widely realized. In addition, the style transfer-based adversarial and backdoor
attack methods show superiority to baselines in many aspects. All the code and
data of this paper can be obtained at https://github.com/thunlp/StyleAttack.