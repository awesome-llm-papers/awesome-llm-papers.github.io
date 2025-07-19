---
layout: publication
title: 'Crome: Multimodal Fake News Detection Using Cross-modal Tri-transformer And
  Metric Learning'
authors: Choi et al.
conference: Proceedings of the ACM Web Conference 2022
year: 2025
bibkey: choi2025crome
citations: 179
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.12422'}]
tags: [Training Techniques, Attention Mechanism, Transformer, Model Architecture,
  Reinforcement Learning, Multimodal Models, Datasets, Merging]
---
Multimodal Fake News Detection has received increasing attention recently.
Existing methods rely on independently encoded unimodal data and overlook the
advantages of capturing intra-modality relationships and integrating
inter-modal similarities using advanced techniques. To address these issues,
Cross-Modal Tri-Transformer and Metric Learning for Multimodal Fake News
Detection (CroMe) is proposed. CroMe utilizes Bootstrapping Language-Image
Pre-training with Frozen Image Encoders and Large Language Models (BLIP2) as
encoders to capture detailed text, image and combined image-text
representations. The metric learning module employs a proxy anchor method to
capture intra-modality relationships while the feature fusion module uses a
Cross-Modal and Tri-Transformer for effective integration. The final fake news
detector processes the fused features through a classifier to predict the
authenticity of the content. Experiments on datasets show that CroMe excels in
multimodal fake news detection.