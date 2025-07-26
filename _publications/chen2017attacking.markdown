---
layout: publication
title: 'Attacking Visual Language Grounding With Adversarial Examples: A Case Study
  On Neural Image Captioning'
authors: Hongge Chen, Huan Zhang, Pin-yu Chen, Jinfeng Yi, Cho-jui Hsieh
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: chen2017attacking
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1712.02051'}]
tags: ["Security"]
short_authors: Chen et al.
---
Visual language grounding is widely studied in modern neural image captioning
systems, which typically adopts an encoder-decoder framework consisting of two
principal components: a convolutional neural network (CNN) for image feature
extraction and a recurrent neural network (RNN) for language caption
generation. To study the robustness of language grounding to adversarial
perturbations in machine vision and perception, we propose Show-and-Fool, a
novel algorithm for crafting adversarial examples in neural image captioning.
The proposed algorithm provides two evaluation approaches, which check whether
neural image captioning systems can be mislead to output some randomly chosen
captions or keywords. Our extensive experiments show that our algorithm can
successfully craft visually-similar adversarial examples with randomly targeted
captions or keywords, and the adversarial examples can be made highly
transferable to other image captioning systems. Consequently, our approach
leads to new robustness implications of neural image captioning and novel
insights in visual language grounding.