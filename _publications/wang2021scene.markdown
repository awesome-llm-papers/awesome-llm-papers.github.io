---
layout: publication
title: 'SGEITL: Scene Graph Enhanced Image-text Learning For Visual Commonsense Reasoning'
authors: Zhecan Wang et al.
conference: AAAI 2022
year: 2021
citations: 20
bibkey: wang2021scene
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.08587'}]
tags: [Training Techniques, Transformer, RAG, Pre-Training, Tools, Attention Mechanism,
  Multimodal Models, Model Architecture]
---
Answering complex questions about images is an ambitious goal for machine
intelligence, which requires a joint understanding of images, text, and
commonsense knowledge, as well as a strong reasoning ability. Recently,
multimodal Transformers have made great progress in the task of Visual
Commonsense Reasoning (VCR), by jointly understanding visual objects and text
tokens through layers of cross-modality attention. However, these approaches do
not utilize the rich structure of the scene and the interactions between
objects which are essential in answering complex commonsense questions. We
propose a Scene Graph Enhanced Image-Text Learning (SGEITL) framework to
incorporate visual scene graphs in commonsense reasoning. To exploit the scene
graph structure, at the model structure level, we propose a multihop graph
transformer for regularizing attention interaction among hops. As for
pre-training, a scene-graph-aware pre-training method is proposed to leverage
structure knowledge extracted in the visual scene graph. Moreover, we introduce
a method to train and generate domain-relevant visual scene graphs using
textual annotations in a weakly-supervised manner. Extensive experiments on VCR
and other tasks show a significant performance boost compared with the
state-of-the-art methods and prove the efficacy of each proposed component.