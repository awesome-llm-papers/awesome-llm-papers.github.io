---
layout: publication
title: Audio Visual Scene-aware Dialog Generation With Transformer-based Video Representations
authors: Yamazaki et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: yamazaki2022audio
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.09979'}]
tags: [Model Architecture, Multimodal Models, CVPR, Transformer]
---
There have been many attempts to build multimodal dialog systems that can
respond to a question about given audio-visual information, and the
representative task for such systems is the Audio Visual Scene-Aware Dialog
(AVSD). Most conventional AVSD models adopt the Convolutional Neural Network
(CNN)-based video feature extractor to understand visual information. While a
CNN tends to obtain both temporally and spatially local information, global
information is also crucial for boosting video understanding because AVSD
requires long-term temporal visual dependency and whole visual information. In
this study, we apply the Transformer-based video feature that can capture both
temporally and spatially global representations more efficiently than the
CNN-based feature. Our AVSD model with its Transformer-based feature attains
higher objective performance scores for answer generation. In addition, our
model achieves a subjective score close to that of human answers in DSTC10. We
observed that the Transformer-based visual feature is beneficial for the AVSD
task because our model tends to correctly answer the questions that need a
temporally and spatially broad range of visual information.