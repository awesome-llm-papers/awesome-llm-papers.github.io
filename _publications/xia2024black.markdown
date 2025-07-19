---
layout: publication
title: Black-box Model Ensembling For Textual And Visual Question Answering Via Information
  Fusion
authors: Xia Yuxi, Zaporojets Kilm, Roth Benjamin
conference: Information Fusion
year: 2024
bibkey: xia2024black
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.12841'}]
tags: [Training Techniques, GPT, Tools, Model Architecture, Fine Tuning, Multimodal
    Models, Datasets, Merging]
---
A diverse range of large language models (LLMs), e.g., ChatGPT, and visual
question answering (VQA) models, e.g., BLIP, have been developed for solving
textual and visual question answering tasks. However, fine-tuning these models
is either difficult, as it requires access via APIs, rendering them as
black-boxes, or costly due to the need of tuning a large number of parameters.
To address this, we introduce InfoSel, a data-efficient ensemble method that
learns to dynamically pick the winner from existing black-box models for
predictions on both textual and multimodal visual question answering tasks.
Unlike traditional ensemble models, InfoSel does not rely on prediction
probabilities or confidences, which typically are not available in black-box
models. Experimental results on four datasets demonstrate that our approach
achieves an absolute increase of up to +5.19% in the F1-score compared to
standalone LLMs using only 1K training instances.