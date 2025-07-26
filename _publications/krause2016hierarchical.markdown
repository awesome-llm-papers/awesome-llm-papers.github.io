---
layout: publication
title: A Hierarchical Approach For Generating Descriptive Image Paragraphs
authors: Jonathan Krause, Justin Johnson, Ranjay Krishna, Li Fei-fei
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2017
bibkey: krause2016hierarchical
citations: 375
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.06607'}]
tags: ["CVPR"]
short_authors: Krause et al.
---
Recent progress on image captioning has made it possible to generate novel
sentences describing images in natural language, but compressing an image into
a single sentence can describe visual content in only coarse detail. While one
new captioning approach, dense captioning, can potentially describe images in
finer levels of detail by captioning many regions within an image, it in turn
is unable to produce a coherent story for an image. In this paper we overcome
these limitations by generating entire paragraphs for describing images, which
can tell detailed, unified stories. We develop a model that decomposes both
images and paragraphs into their constituent parts, detecting semantic regions
in images and using a hierarchical recurrent neural network to reason about
language. Linguistic analysis confirms the complexity of the paragraph
generation task, and thorough experiments on a new dataset of image and
paragraph pairs demonstrate the effectiveness of our approach.