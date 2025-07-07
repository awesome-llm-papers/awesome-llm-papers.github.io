---
layout: publication
title: Vision-and-language Or Vision-for-language? On Cross-modal Influence In Multimodal
  Transformers
authors: Stella Frank, Emanuele Bugliarello, Desmond Elliott
conference: Arxiv
year: 2021
citations: 18
bibkey: frank2021vision
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04448'}]
tags: [Masked Language Model, Training Techniques, Transformer, BERT, Multimodal Models,
  Model Architecture]
---
Pretrained vision-and-language BERTs aim to learn representations that
combine information from both modalities. We propose a diagnostic method based
on cross-modal input ablation to assess the extent to which these models
actually integrate cross-modal information. This method involves ablating
inputs from one modality, either entirely or selectively based on cross-modal
grounding alignments, and evaluating the model prediction performance on the
other modality. Model performance is measured by modality-specific tasks that
mirror the model pretraining objectives (e.g. masked language modelling for
text). Models that have learned to construct cross-modal representations using
both modalities are expected to perform worse when inputs are missing from a
modality. We find that recently proposed models have much greater relative
difficulty predicting text when visual information is ablated, compared to
predicting visual object categories when text is ablated, indicating that these
models are not symmetrically cross-modal.