---
layout: publication
title: Towards A Visual-language Foundation Model For Computational Pathology
authors: Lu et al.
conference: Nature Medicine
year: 2023
bibkey: lu2023towards
citations: 218
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.12914'}]
tags: [RAG, Training Techniques, Evaluation, Fine Tuning, Datasets]
---
The accelerated adoption of digital pathology and advances in deep learning
have enabled the development of powerful models for various pathology tasks
across a diverse array of diseases and patient cohorts. However, model training
is often difficult due to label scarcity in the medical domain and the model's
usage is limited by the specific task and disease for which it is trained.
Additionally, most models in histopathology leverage only image data, a stark
contrast to how humans teach each other and reason about histopathologic
entities. We introduce CONtrastive learning from Captions for Histopathology
(CONCH), a visual-language foundation model developed using diverse sources of
histopathology images, biomedical text, and notably over 1.17 million
image-caption pairs via task-agnostic pretraining. Evaluated on a suite of 13
diverse benchmarks, CONCH can be transferred to a wide range of downstream
tasks involving either or both histopathology images and text, achieving
state-of-the-art performance on histology image classification, segmentation,
captioning, text-to-image and image-to-text retrieval. CONCH represents a
substantial leap over concurrent visual-language pretrained systems for
histopathology, with the potential to directly facilitate a wide array of
machine learning-based workflows requiring minimal or no further supervised
fine-tuning.