---
layout: publication
title: 'Lightner: A Lightweight Tuning Paradigm For Low-resource NER Via Pluggable
  Prompting'
authors: Xiang Chen et al.
conference: Arxiv
year: 2021
citations: 26
bibkey: chen2021lightweight
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.00720'}, {name: Code,
    url: 'https://github.com/zjunlp/DeepKE/tree/main/example/ner/few-shot'}]
tags: [Training Techniques, Transformer, Few-Shot, Attention Mechanism, Has Code,
  Prompting, Model Architecture]
---
Most NER methods rely on extensive labeled data for model training, which
struggles in the low-resource scenarios with limited training data. Existing
dominant approaches usually suffer from the challenge that the target domain
has different label sets compared with a resource-rich source domain, which can
be concluded as class transfer and domain transfer. In this paper, we propose a
lightweight tuning paradigm for low-resource NER via pluggable prompting
(LightNER). Specifically, we construct the unified learnable verbalizer of
entity categories to generate the entity span sequence and entity categories
without any label-specific classifiers, thus addressing the class transfer
issue. We further propose a pluggable guidance module by incorporating
learnable parameters into the self-attention layer as guidance, which can
re-modulate the attention and adapt pre-trained weights. Note that we only tune
those inserted module with the whole parameter of the pre-trained language
model fixed, thus, making our approach lightweight and flexible for
low-resource scenarios and can better transfer knowledge across domains.
Experimental results show that LightNER can obtain comparable performance in
the standard supervised setting and outperform strong baselines in low-resource
settings. Code is in
https://github.com/zjunlp/DeepKE/tree/main/example/ner/few-shot.