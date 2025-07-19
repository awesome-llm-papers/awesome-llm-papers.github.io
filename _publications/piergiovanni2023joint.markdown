---
layout: publication
title: Joint Adaptive Representations For Image-language Learning
authors: Piergiovanni Aj, Angelova Anelia
conference: 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: piergiovanni2023joint
citations: 503
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.19924'}]
tags: [Training Techniques, CVPR, Efficiency And Optimization, Multimodal Models,
  Datasets, Merging]
---
Image-language learning has made unprecedented progress in visual
understanding. These developments have come at high costs, as contemporary
vision-language models require large model scales and amounts of data. We here
propose a much easier recipe for image-language learning, which produces
effective models, outperforming bigger and more expensive ones, often trained
on orders of magnitude larger datasets. Our key finding is the joint learning
of a compact vision and language representation, which adaptively and
iteratively fuses the multi-modal features. This results in a more effective
image-language learning, greatly lowering the FLOPs by combining and reducing
the number of tokens for both text and images, e.g. a 33% reduction in FLOPs
is achieved, compared to baseline fusion techniques used by popular
image-language models, while improving performance. This also allows the model
to scale without a large increase in FLOPs or memory. In addition, we propose
adaptive pre-training data sampling which improves the data efficiency. The
proposed approach achieves competitive performance compared to much larger
models, and does so with significantly less data and FLOPs. With only 40M
training examples and with 39 GFLOPs our lightweight model outperforms many
times larger state-of-the-art models of 2-20x more FLOPs and using bigger
datasets some of which with close to 1B training examples.