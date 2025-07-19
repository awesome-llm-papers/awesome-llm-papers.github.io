---
layout: publication
title: 'Data Curation Matters: Model Collapse And Spurious Shift Performance Prediction
  From Training On Uncurated Text Embeddings'
authors: Mattioli et al.
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: mattioli2025data
citations: 170
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.17989'}]
tags: [Training Techniques, Reinforcement Learning, Evaluation, ICCV]
---
Training models on uncurated Text Embeddings (TEs) derived from raw tabular data can lead to a severe failure mode known as model collapse, where predictions converge to a single class regardless of input. By comparing models trained with identical hyper-parameter configurations on both raw tabular data and their TE-derived counterparts, we find that collapse is a consistent failure mode in the latter setting. We introduce a set of metrics that capture the extent of model collapse, offering a new perspective on TE quality as a proxy for data curation. Our results reveal that TE alone does not effectively function as a curation layer - and that their quality significantly influences downstream learning. More insidiously, we observe that the presence of model collapse can yield artificially inflated and spurious Accuracy-on-the-Line correlation. These findings highlight the need for more nuanced curation and evaluation of embedding-based representations, particularly in out-of-distribution settings.