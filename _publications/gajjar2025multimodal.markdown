---
layout: publication
title: Multimodal Sentiment Analysis On CMU-MOSEI Dataset Using Transformer-based
  Models
authors: Gajjar Jugal, Ranaware Kaustik
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2025
bibkey: gajjar2025multimodal
citations: 449
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.06110'}]
tags: [Security, Model Architecture, Merging, Interpretability And Explainability,
  Training Techniques, Efficiency And Optimization, BERT, Evaluation, ACL, Transformer,
  Multimodal Models, Datasets, Reinforcement Learning]
---
This project performs multimodal sentiment analysis using the CMU-MOSEI dataset, using transformer-based models with early fusion to integrate text, audio, and visual modalities. We employ BERT-based encoders for each modality, extracting embeddings that are concatenated before classification. The model achieves strong performance, with 97.87% 7-class accuracy and a 0.9682 F1-score on the test set, demonstrating the effectiveness of early fusion in capturing cross-modal interactions. The training utilized Adam optimization (lr=1e-4), dropout (0.3), and early stopping to ensure generalization and robustness. Results highlight the superiority of transformer architectures in modeling multimodal sentiment, with a low MAE (0.1060) indicating precise sentiment intensity prediction. Future work may compare fusion strategies or enhance interpretability. This approach utilizes multimodal learning by effectively combining linguistic, acoustic, and visual cues for sentiment analysis.