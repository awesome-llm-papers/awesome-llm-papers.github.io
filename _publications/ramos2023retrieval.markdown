---
layout: publication
title: Retrieval-augmented Image Captioning
authors: Rita Ramos, Desmond Elliott, Bruno Martins
conference: Proceedings of the 17th Conference of the European Chapter of the Association
  for Computational Linguistics
year: 2023
citations: 16
bibkey: ramos2023retrieval
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.08268'}]
tags: [Model Architecture, RAG, Reinforcement Learning, Multimodal Models, BERT, Training
    Techniques]
---
Inspired by retrieval-augmented language generation and pretrained Vision and
Language (V&L) encoders, we present a new approach to image captioning that
generates sentences given the input image and a set of captions retrieved from
a datastore, as opposed to the image alone. The encoder in our model jointly
processes the image and retrieved captions using a pretrained V&L BERT, while
the decoder attends to the multimodal encoder representations, benefiting from
the extra textual evidence from the retrieved captions. Experimental results on
the COCO dataset show that image captioning can be effectively formulated from
this new perspective. Our model, named EXTRA, benefits from using captions
retrieved from the training dataset, and it can also benefit from using an
external dataset without the need for retraining. Ablation studies show that
retrieving a sufficient number of captions (e.g., k=5) can improve captioning
quality. Our work contributes towards using pretrained V&L encoders for
generative tasks, instead of standard classification tasks.