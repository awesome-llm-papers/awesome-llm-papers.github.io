---
layout: publication
title: 'Multi-scale Vision Longformer: A New Vision Transformer For High-resolution
  Image Encoding'
authors: Zhang et al.
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: zhang2021multi
citations: 265
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.15358'}]
tags: [Model Architecture, ICCV, Attention Mechanism, Transformer]
---
This paper presents a new Vision Transformer (ViT) architecture Multi-Scale
Vision Longformer, which significantly enhances the ViT of
\cite\{dosovitskiy2020image\} for encoding high-resolution images using two
techniques. The first is the multi-scale model structure, which provides image
encodings at multiple scales with manageable computational cost. The second is
the attention mechanism of vision Longformer, which is a variant of Longformer
\cite\{beltagy2020longformer\}, originally developed for natural language
processing, and achieves a linear complexity w.r.t. the number of input tokens.
A comprehensive empirical study shows that the new ViT significantly
outperforms several strong baselines, including the existing ViT models and
their ResNet counterparts, and the Pyramid Vision Transformer from a concurrent
work \cite\{wang2021pyramid\}, on a range of vision tasks, including image
classification, object detection, and segmentation. The models and source code
are released at https://github.com/microsoft/vision-longformer.