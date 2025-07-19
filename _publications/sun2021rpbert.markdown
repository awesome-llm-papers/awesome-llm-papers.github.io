---
layout: publication
title: 'Rpbert: A Text-image Relation Propagation-based BERT Model For Multimodal
  NER'
authors: Sun et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: sun2021rpbert
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.02967'}]
tags: [Attention Mechanism, BERT, Transformer, Model Architecture, Multimodal Models,
  AAAI, Datasets]
---
Recently multimodal named entity recognition (MNER) has utilized images to
improve the accuracy of NER in tweets. However, most of the multimodal methods
use attention mechanisms to extract visual clues regardless of whether the text
and image are relevant. Practically, the irrelevant text-image pairs account
for a large proportion in tweets. The visual clues that are unrelated to the
texts will exert uncertain or even negative effects on multimodal model
learning. In this paper, we introduce a method of text-image relation
propagation into the multimodal BERT model. We integrate soft or hard gates to
select visual clues and propose a multitask algorithm to train on the MNER
datasets. In the experiments, we deeply analyze the changes in visual attention
before and after the use of text-image relation propagation. Our model achieves
state-of-the-art performance on the MNER datasets.