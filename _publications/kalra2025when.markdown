---
layout: publication
title: When Can You Get Away With Low Memory Adam?
authors: Kalra et al.
conference: Information, Communication &amp; Society
year: 2025
bibkey: kalra2025when
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.01843'}]
tags: [Model Architecture, RAG, Training Techniques, Datasets]
---
Adam is the go-to optimizer for training modern machine learning models, but
it requires additional memory to maintain the moving averages of the gradients
and their squares. While various low-memory optimizers have been proposed that
sometimes match the performance of Adam, their lack of reliability has left
Adam as the default choice. In this work, we apply a simple layer-wise
Signal-to-Noise Ratio (SNR) analysis to quantify when second-moment tensors can
be effectively replaced by their means across different dimensions. Our SNR
analysis reveals how architecture, training hyperparameters, and dataset
properties impact compressibility along Adam's trajectory, naturally leading to
\\(\textit\{SlimAdam\}\\), a memory-efficient Adam variant. \\(\textit\{SlimAdam\}\\)
compresses the second moments along dimensions with high SNR when feasible, and
leaves when compression would be detrimental. Through experiments across a
diverse set of architectures and training scenarios, we show that
\\(\textit\{SlimAdam\}\\) matches Adam's performance and stability while saving up to
\\(98%\\) of total second moments. Code for \\(\textit\{SlimAdam\}\\) is available at
https://github.com/dayal-kalra/low-memory-adam.