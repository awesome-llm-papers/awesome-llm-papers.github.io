---
layout: publication
title: Visual Language Pretrained Multiple Instance Zero-shot Transfer For Histopathology
  Images
authors: Lu et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: lu2023visual
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.07831'}]
tags: [RAG, Training Techniques, Tools, CVPR, Reinforcement Learning, Datasets, Merging]
---
Contrastive visual language pretraining has emerged as a powerful method for
either training new language-aware image encoders or augmenting existing
pretrained models with zero-shot visual recognition capabilities. However,
existing works typically train on large datasets of image-text pairs and have
been designed to perform downstream tasks involving only small to medium
sized-images, neither of which are applicable to the emerging field of
computational pathology where there are limited publicly available paired
image-text datasets and each image can span up to 100,000 x 100,000 pixels. In
this paper we present MI-Zero, a simple and intuitive framework for unleashing
the zero-shot transfer capabilities of contrastively aligned image and text
models on gigapixel histopathology whole slide images, enabling multiple
downstream diagnostic tasks to be carried out by pretrained encoders without
requiring any additional labels. MI-Zero reformulates zero-shot transfer under
the framework of multiple instance learning to overcome the computational
challenge of inference on extremely large images. We used over 550k pathology
reports and other available in-domain text corpora to pre-train our text
encoder. By effectively leveraging strong pre-trained encoders, our best model
pretrained on over 33k histopathology image-caption pairs achieves an average
median zero-shot accuracy of 70.2% across three different real-world cancer
subtyping tasks. Our code is available at:
https://github.com/mahmoodlab/MI-Zero.