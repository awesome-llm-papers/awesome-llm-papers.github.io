---
layout: publication
title: Iterative Answer Prediction With Pointer-augmented Multimodal Transformers
  For Textvqa
authors: Hu et al.
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: hu2019iterative
citations: 188
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.06258'}]
tags: [Attention Mechanism, Evaluation, CVPR, Transformer, Model Architecture, Multimodal
    Models, Datasets, Merging]
---
Many visual scenes contain text that carries crucial information, and it is
thus essential to understand text in images for downstream reasoning tasks. For
example, a deep water label on a warning sign warns people about the danger in
the scene. Recent work has explored the TextVQA task that requires reading and
understanding text in images to answer a question. However, existing approaches
for TextVQA are mostly based on custom pairwise fusion mechanisms between a
pair of two modalities and are restricted to a single prediction step by
casting TextVQA as a classification task. In this work, we propose a novel
model for the TextVQA task based on a multimodal transformer architecture
accompanied by a rich representation for text in images. Our model naturally
fuses different modalities homogeneously by embedding them into a common
semantic space where self-attention is applied to model inter- and intra-
modality context. Furthermore, it enables iterative answer decoding with a
dynamic pointer network, allowing the model to form an answer through
multi-step prediction instead of one-step classification. Our model outperforms
existing approaches on three benchmark datasets for the TextVQA task by a large
margin.