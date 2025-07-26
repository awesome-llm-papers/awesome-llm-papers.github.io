---
layout: publication
title: Modulating Early Visual Processing By Language
authors: "Harm de Vries, Florian Strub, J\xE9r\xE9mie Mary, Hugo Larochelle, Olivier\
  \ Pietquin, Aaron Courville"
conference: Arxiv
year: 2017
bibkey: devries2017modulating
citations: 235
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.00683'}]
tags: []
short_authors: Vries et al.
---
It is commonly assumed that language refers to high-level visual concepts
while leaving low-level visual processing unaffected. This view dominates the
current literature in computational models for language-vision tasks, where
visual and linguistic input are mostly processed independently before being
fused into a single representation. In this paper, we deviate from this classic
pipeline and propose to modulate the *entire visual processing* by
linguistic input. Specifically, we condition the batch normalization parameters
of a pretrained residual network (ResNet) on a language embedding. This
approach, which we call MOdulated RESnet (\MRN), significantly improves strong
baselines on two visual question answering tasks. Our ablation study shows that
modulating from the early stages of the visual processing is beneficial.