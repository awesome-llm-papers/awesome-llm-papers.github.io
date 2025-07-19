---
layout: publication
title: Taming Transformers For High-resolution Image Synthesis
authors: "Esser Patrick, Rombach Robin, Ommer Bj\xF6rn"
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: esser2020taming
citations: 1401
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.09841'}]
tags: [GPT, Tools, CVPR, Ethics And Bias, Transformer, Model Architecture, Language
    Modeling]
---
Designed to learn long-range interactions on sequential data, transformers
continue to show state-of-the-art results on a wide variety of tasks. In
contrast to CNNs, they contain no inductive bias that prioritizes local
interactions. This makes them expressive, but also computationally infeasible
for long sequences, such as high-resolution images. We demonstrate how
combining the effectiveness of the inductive bias of CNNs with the expressivity
of transformers enables them to model and thereby synthesize high-resolution
images. We show how to (i) use CNNs to learn a context-rich vocabulary of image
constituents, and in turn (ii) utilize transformers to efficiently model their
composition within high-resolution images. Our approach is readily applied to
conditional synthesis tasks, where both non-spatial information, such as object
classes, and spatial information, such as segmentations, can control the
generated image. In particular, we present the first results on
semantically-guided synthesis of megapixel images with transformers and obtain
the state of the art among autoregressive models on class-conditional ImageNet.
Code and pretrained models can be found at
https://github.com/CompVis/taming-transformers .