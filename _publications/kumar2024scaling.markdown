---
layout: publication
title: Scaling Laws For Precision
authors: Kumar et al.
conference: Physical Review A
year: 2024
bibkey: kumar2024scaling
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.04330'}]
tags: [Scaling Laws, Training Techniques, Efficiency And Optimization, Large Scale
    Training, Quantization]
---
Low precision training and inference affect both the quality and cost of
language models, but current scaling laws do not account for this. In this
work, we devise "precision-aware" scaling laws for both training and inference.
We propose that training in lower precision reduces the model's "effective
parameter count," allowing us to predict the additional loss incurred from
training in low precision and post-train quantization. For inference, we find
that the degradation introduced by post-training quantization increases as
models are trained on more data, eventually making additional pretraining data
actively harmful. For training, our scaling laws allow us to predict the loss
of a model with different parts in different precisions, and suggest that
training larger models in lower precision may be compute optimal. We unify the
scaling laws for post and pretraining quantization to arrive at a single
functional form that predicts degradation from training and inference in varied
precisions. We fit on over 465 pretraining runs and validate our predictions on
model sizes up to 1.7B parameters trained on up to 26B tokens.