---
layout: publication
title: 'LAVT: Language-aware Vision Transformer For Referring Image Segmentation'
authors: Yang et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: yang2021lavt
citations: 170
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.02244'}]
tags: [RAG, CVPR, Transformer, Model Architecture, Reinforcement Learning, Multimodal
    Models, Merging]
---
Referring image segmentation is a fundamental vision-language task that aims
to segment out an object referred to by a natural language expression from an
image. One of the key challenges behind this task is leveraging the referring
expression for highlighting relevant positions in the image. A paradigm for
tackling this problem is to leverage a powerful vision-language ("cross-modal")
decoder to fuse features independently extracted from a vision encoder and a
language encoder. Recent methods have made remarkable advancements in this
paradigm by exploiting Transformers as cross-modal decoders, concurrent to the
Transformer's overwhelming success in many other vision-language tasks.
Adopting a different approach in this work, we show that significantly better
cross-modal alignments can be achieved through the early fusion of linguistic
and visual features in intermediate layers of a vision Transformer encoder
network. By conducting cross-modal feature fusion in the visual feature
encoding stage, we can leverage the well-proven correlation modeling power of a
Transformer encoder for excavating helpful multi-modal context. This way,
accurate segmentation results are readily harvested with a light-weight mask
predictor. Without bells and whistles, our method surpasses the previous
state-of-the-art methods on RefCOCO, RefCOCO+, and G-Ref by large margins.