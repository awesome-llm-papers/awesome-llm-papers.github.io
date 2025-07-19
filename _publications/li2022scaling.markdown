---
layout: publication
title: Scaling Language-image Pre-training Via Masking
authors: Li et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: li2022scaling
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.00794'}]
tags: [RAG, Training Techniques, CVPR, Multimodal Models]
---
We present Fast Language-Image Pre-training (FLIP), a simple and more
efficient method for training CLIP. Our method randomly masks out and removes a
large portion of image patches during training. Masking allows us to learn from
more image-text pairs given the same wall-clock time and contrast more samples
per iteration with similar memory footprint. It leads to a favorable trade-off
between accuracy and training time. In our experiments on 400 million
image-text pairs, FLIP improves both accuracy and speed over the no-masking
baseline. On a large diversity of downstream tasks, FLIP dominantly outperforms
the CLIP counterparts trained on the same data. Facilitated by the speedup, we
explore the scaling behavior of increasing the model size, data size, or
training length, and report encouraging results and comparisons. We hope that
our work will foster future research on scaling vision-language learning.