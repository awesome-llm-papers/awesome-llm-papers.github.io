---
layout: publication
title: 'Skeleton Key: Image Captioning By Skeleton-attribute Decomposition'
authors: Yufei Wang, Zhe Lin, Xiaohui Shen, Scott Cohen, Garrison W. Cottrell
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2017
bibkey: wang2017skeleton
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.06972'}]
tags: ["CVPR"]
short_authors: Wang et al.
---
Recently, there has been a lot of interest in automatically generating
descriptions for an image. Most existing language-model based approaches for
this task learn to generate an image description word by word in its original
word order. However, for humans, it is more natural to locate the objects and
their relationships first, and then elaborate on each object, describing
notable attributes. We present a coarse-to-fine method that decomposes the
original image description into a skeleton sentence and its attributes, and
generates the skeleton sentence and attribute phrases separately. By this
decomposition, our method can generate more accurate and novel descriptions
than the previous state-of-the-art. Experimental results on the MS-COCO and a
larger scale Stock3M datasets show that our algorithm yields consistent
improvements across different evaluation metrics, especially on the SPICE
metric, which has much higher correlation with human ratings than the
conventional metrics. Furthermore, our algorithm can generate descriptions with
varied length, benefiting from the separate control of the skeleton and
attributes. This enables image description generation that better accommodates
user preferences.