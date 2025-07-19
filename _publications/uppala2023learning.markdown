---
layout: publication
title: Learning Video Embedding Space With Natural Language Supervision
authors: Uppala et al.
conference: ICASSP 2023 - 2023 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2023
bibkey: uppala2023learning
citations: 140
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.14584'}]
tags: [ICASSP, Evaluation, Datasets]
---
The recent success of the CLIP model has shown its potential to be applied to
a wide range of vision and language tasks. However this only establishes
embedding space relationship of language to images, not to the video domain. In
this paper, we propose a novel approach to map video embedding space to natural
langugage. We propose a two-stage approach that first extracts visual features
from each frame of a video using a pre-trained CNN, and then uses the CLIP
model to encode the visual features for the video domain, along with the
corresponding text descriptions. We evaluate our method on two benchmark
datasets, UCF101 and HMDB51, and achieve state-of-the-art performance on both
tasks.