---
layout: publication
title: 'Contextual Augmentation: Data Augmentation By Words With Paradigmatic Relations'
authors: Kobayashi Sosuke
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 2
  (Short Papers)'
year: 2018
bibkey: kobayashi2018contextual
citations: 575
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.06201'}]
tags: [ACL, Model Architecture]
---
We propose a novel data augmentation for labeled sentences called contextual
augmentation. We assume an invariance that sentences are natural even if the
words in the sentences are replaced with other words with paradigmatic
relations. We stochastically replace words with other words that are predicted
by a bi-directional language model at the word positions. Words predicted
according to a context are numerous but appropriate for the augmentation of the
original words. Furthermore, we retrofit a language model with a
label-conditional architecture, which allows the model to augment sentences
without breaking the label-compatibility. Through the experiments for six
various different text classification tasks, we demonstrate that the proposed
method improves classifiers based on the convolutional or recurrent neural
networks.