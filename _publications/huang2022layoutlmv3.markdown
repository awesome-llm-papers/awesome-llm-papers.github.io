---
layout: publication
title: 'Layoutlmv3: Pre-training For Document AI With Unified Text And Image Masking'
authors: Yupan Huang, Tengchao Lv, Lei Cui, Yutong Lu, Furu Wei
conference: Proceedings of the 30th ACM International Conference on Multimedia
year: 2022
bibkey: huang2022layoutlmv3
citations: 270
additional_links: [{name: Code, url: 'https://aka.ms/layoutlmv3'}, {name: Paper, url: 'https://arxiv.org/abs/2204.08387'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Huang et al.
---
Self-supervised pre-training techniques have achieved remarkable progress in
Document AI. Most multimodal pre-trained models use a masked language modeling
objective to learn bidirectional representations on the text modality, but they
differ in pre-training objectives for the image modality. This discrepancy adds
difficulty to multimodal representation learning. In this paper, we propose
\textbf\{LayoutLMv3\} to pre-train multimodal Transformers for Document AI with
unified text and image masking. Additionally, LayoutLMv3 is pre-trained with a
word-patch alignment objective to learn cross-modal alignment by predicting
whether the corresponding image patch of a text word is masked. The simple
unified architecture and training objectives make LayoutLMv3 a general-purpose
pre-trained model for both text-centric and image-centric Document AI tasks.
Experimental results show that LayoutLMv3 achieves state-of-the-art performance
not only in text-centric tasks, including form understanding, receipt
understanding, and document visual question answering, but also in
image-centric tasks such as document image classification and document layout
analysis. The code and models are publicly available at
https://aka.ms/layoutlmv3.