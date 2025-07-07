---
layout: publication
title: Controllable Natural Language Generation With Contrastive Prefixes
authors: Jing Qian, Li Dong, Yelong Shen, Furu Wei, Weizhu Chen
conference: Arxiv
year: 2022
citations: 19
bibkey: qian2022controllable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.13257'}]
tags: [GPT, Training Techniques, Fine-Tuning, Tools, Model Architecture]
---
To guide the generation of large pretrained language models (LM), previous
work has focused on directly fine-tuning the language model or utilizing an
attribute discriminator. In this work, we propose a novel lightweight framework
for controllable GPT2 generation, which utilizes a set of small
attribute-specific vectors, called prefixes, to steer natural language
generation. Different from prefix-tuning, where each prefix is trained
independently, we take the relationship among prefixes into consideration and
train multiple prefixes simultaneously. We propose a novel supervised method
and also an unsupervised method to train the prefixes for single-aspect control
while the combination of these two methods can achieve multi-aspect control.
Experimental results on both single-aspect and multi-aspect control show that
our methods can guide generation towards the desired attributes while keeping
high linguistic quality.