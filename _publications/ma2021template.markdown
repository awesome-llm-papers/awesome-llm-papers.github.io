---
layout: publication
title: Template-free Prompt Tuning For Few-shot NER
authors: Ruotian Ma, Xin Zhou, Tao Gui, Yiding Tan, Linyang Li, Qi Zhang, Xuanjing
  Huang
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2022
bibkey: ma2021template
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.13532'}]
tags: ["Few-Shot", "Fine-Tuning", "NAACL", "Prompting", "Training Techniques"]
short_authors: Ma et al.
---
Prompt-based methods have been successfully applied in sentence-level
few-shot learning tasks, mostly owing to the sophisticated design of templates
and label words. However, when applied to token-level labeling tasks such as
NER, it would be time-consuming to enumerate the template queries over all
potential entity spans. In this work, we propose a more elegant method to
reformulate NER tasks as LM problems without any templates. Specifically, we
discard the template construction process while maintaining the word prediction
paradigm of pre-training models to predict a class-related pivot word (or label
word) at the entity position. Meanwhile, we also explore principled ways to
automatically search for appropriate label words that the pre-trained models
can easily adapt to. While avoiding complicated template-based process, the
proposed LM objective also reduces the gap between different objectives used in
pre-training and fine-tuning, thus it can better benefit the few-shot
performance. Experimental results demonstrate the effectiveness of the proposed
method over bert-tagger and template-based method under few-shot setting.
Moreover, the decoding speed of the proposed method is up to 1930.12 times
faster than the template-based method.