---
layout: publication
title: An Exploration Of Hierarchical Attention Transformers For Efficient Long Document
  Classification
authors: Chalkidis et al.
conference: 2019 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
year: 2022
bibkey: chalkidis2022exploration
citations: 124
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.05529'}]
tags: [Attention Mechanism, Alt, ASRU, Transformer, Model Architecture, Efficiency
    And Optimization, Reinforcement Learning, Fine Tuning]
---
Non-hierarchical sparse attention Transformer-based models, such as
Longformer and Big Bird, are popular approaches to working with long documents.
There are clear benefits to these approaches compared to the original
Transformer in terms of efficiency, but Hierarchical Attention Transformer
(HAT) models are a vastly understudied alternative. We develop and release
fully pre-trained HAT models that use segment-wise followed by cross-segment
encoders and compare them with Longformer models and partially pre-trained
HATs. In several long document downstream classification tasks, our best HAT
model outperforms equally-sized Longformer models while using 10-20% less GPU
memory and processing documents 40-45% faster. In a series of ablation studies,
we find that HATs perform best with cross-segment contextualization throughout
the model than alternative configurations that implement either early or late
cross-segment contextualization. Our code is on GitHub:
https://github.com/coastalcph/hierarchical-transformers.