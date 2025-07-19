---
layout: publication
title: 'Segearth-r1: Geospatial Pixel Reasoning Via Large Language Model'
authors: Li et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: li2025segearth
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.09644'}]
tags: [CVPR, Evaluation, Datasets]
---
Remote sensing has become critical for understanding environmental dynamics,
urban planning, and disaster management. However, traditional remote sensing
workflows often rely on explicit segmentation or detection methods, which
struggle to handle complex, implicit queries that require reasoning over
spatial context, domain knowledge, and implicit user intent. Motivated by this,
we introduce a new task, \ie, geospatial pixel reasoning, which allows implicit
querying and reasoning and generates the mask of the target region. To advance
this task, we construct and release the first large-scale benchmark dataset
called EarthReason, which comprises 5,434 manually annotated image masks with
over 30,000 implicit question-answer pairs. Moreover, we propose SegEarth-R1, a
simple yet effective language-guided segmentation baseline that integrates a
hierarchical visual encoder, a large language model (LLM) for instruction
parsing, and a tailored mask generator for spatial correlation. The design of
SegEarth-R1 incorporates domain-specific adaptations, including aggressive
visual token compression to handle ultra-high-resolution remote sensing images,
a description projection module to fuse language and multi-scale features, and
a streamlined mask prediction pipeline that directly queries description
embeddings. Extensive experiments demonstrate that SegEarth-R1 achieves
state-of-the-art performance on both reasoning and referring segmentation
tasks, significantly outperforming traditional and LLM-based segmentation
methods. Our data and code will be released at
https://github.com/earth-insights/SegEarth-R1.