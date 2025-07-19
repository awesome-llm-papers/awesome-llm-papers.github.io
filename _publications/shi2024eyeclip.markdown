---
layout: publication
title: 'Eyeclip: A Visual-language Foundation Model For Multi-modal Ophthalmic Image
  Analysis'
authors: Shi et al.
conference: Nature Medicine
year: 2024
bibkey: shi2024eyeclip
citations: 282
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.06644'}]
tags: [RAG, Training Techniques, Evaluation, Few Shot, Reinforcement Learning, Multimodal
    Models, Datasets]
---
Early detection of eye diseases like glaucoma, macular degeneration, and
diabetic retinopathy is crucial for preventing vision loss. While artificial
intelligence (AI) foundation models hold significant promise for addressing
these challenges, existing ophthalmic foundation models primarily focus on a
single modality, whereas diagnosing eye diseases requires multiple modalities.
A critical yet often overlooked aspect is harnessing the multi-view information
across various modalities for the same patient. Additionally, due to the
long-tail nature of ophthalmic diseases, standard fully supervised or
unsupervised learning approaches often struggle. Therefore, it is essential to
integrate clinical text to capture a broader spectrum of diseases. We propose
EyeCLIP, a visual-language foundation model developed using over 2.77 million
multi-modal ophthalmology images with partial text data. To fully leverage the
large multi-modal unlabeled and labeled data, we introduced a pretraining
strategy that combines self-supervised reconstructions, multi-modal image
contrastive learning, and image-text contrastive learning to learn a shared
representation of multiple modalities. Through evaluation using 14 benchmark
datasets, EyeCLIP can be transferred to a wide range of downstream tasks
involving ocular and systemic diseases, achieving state-of-the-art performance
in disease classification, visual question answering, and cross-modal
retrieval. EyeCLIP represents a significant advancement over previous methods,
especially showcasing few-shot, even zero-shot capabilities in real-world
long-tail scenarios.