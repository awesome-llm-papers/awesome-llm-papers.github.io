---
layout: publication
title: 'From Pixels To Objects: Cubic Visual Attention For Visual Question Answering'
authors: Song et al.
conference: Proceedings of the Twenty-Seventh International Joint Conference on Artificial
  Intelligence
year: 2022
bibkey: song2022pixels
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.01923'}]
tags: [Model Architecture, AAAI, Transformer, IJCAI, Datasets, Attention Mechanism]
---
Recently, attention-based Visual Question Answering (VQA) has achieved great
success by utilizing question to selectively target different visual areas that
are related to the answer. Existing visual attention models are generally
planar, i.e., different channels of the last conv-layer feature map of an image
share the same weight. This conflicts with the attention mechanism because CNN
features are naturally spatial and channel-wise. Also, visual attention models
are usually conducted on pixel-level, which may cause region discontinuous
problems. In this paper, we propose a Cubic Visual Attention (CVA) model by
successfully applying a novel channel and spatial attention on object regions
to improve VQA task. Specifically, instead of attending to pixels, we first
take advantage of the object proposal networks to generate a set of object
candidates and extract their associated conv features. Then, we utilize the
question to guide channel attention and spatial attention calculation based on
the con-layer feature map. Finally, the attended visual features and the
question are combined to infer the answer. We assess the performance of our
proposed CVA on three public image QA datasets, including COCO-QA, VQA and
Visual7W. Experimental results show that our proposed method significantly
outperforms the state-of-the-arts.