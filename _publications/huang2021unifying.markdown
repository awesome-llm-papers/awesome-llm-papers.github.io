---
layout: publication
title: Unifying Multimodal Transformer For Bi-directional Image And Text Generation
authors: Yupan Huang, Hongwei Xue, Bei Liu, Yutong Lu
conference: Arxiv
year: 2021
citations: 28
bibkey: huang2021unifying
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.09753'}]
tags: [Training Techniques, Transformer, Tools, Multimodal Models, Language Modeling,
  Model Architecture]
---
We study the joint learning of image-to-text and text-to-image generations,
which are naturally bi-directional tasks. Typical existing works design two
separate task-specific models for each task, which impose expensive design
efforts. In this work, we propose a unified image-and-text generative framework
based on a single multimodal model to jointly study the bi-directional tasks.
We adopt Transformer as our unified architecture for its strong performance and
task-agnostic design. Specifically, we formulate both tasks as sequence
generation tasks, where we represent images and text as unified sequences of
tokens, and the Transformer learns multimodal interactions to generate
sequences. We further propose two-level granularity feature representations and
sequence-level training to improve the Transformer-based unified framework.
Experiments show that our approach significantly improves previous
Transformer-based model X-LXMERT's FID from 37.0 to 29.9 (lower is better) for
text-to-image generation, and improves CIDEr-D score from 100.9% to 122.6% for
fine-tuned image-to-text generation on the MS-COCO dataset. Our code is
available online.