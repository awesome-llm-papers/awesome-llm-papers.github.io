---
layout: publication
title: Visual In-context Prompting
authors: Li et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: li2023visual
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.13601'}]
tags: [Training Techniques, Prompting, Tools, CVPR, Model Architecture, Reinforcement
    Learning, Fine Tuning, Datasets]
---
In-context prompting in large language models (LLMs) has become a prevalent
approach to improve zero-shot capabilities, but this idea is less explored in
the vision domain. Existing visual prompting methods focus on referring
segmentation to segment the most relevant object, falling short of addressing
many generic vision tasks like open-set segmentation and detection. In this
paper, we introduce a universal visual in-context prompting framework for both
tasks. In particular, we build on top of an encoder-decoder architecture, and
develop a versatile prompt encoder to support a variety of prompts like
strokes, boxes, and points. We further enhance it to take an arbitrary number
of reference image segments as the context. Our extensive explorations show
that the proposed visual in-context prompting elicits extraordinary referring
and generic segmentation capabilities to refer and detect, yielding competitive
performance to close-set in-domain datasets and showing promising results on
many open-set segmentation datasets. By joint training on COCO and SA-1B, our
model achieves \\(57.7\\) PQ on COCO and \\(23.2\\) PQ on ADE20K. Code will be
available at https://github.com/UX-Decoder/DINOv.