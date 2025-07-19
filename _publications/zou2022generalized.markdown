---
layout: publication
title: Generalized Decoding For Pixel, Image, And Language
authors: Zou et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: zou2022generalized
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.11270'}]
tags: [Training Techniques, CVPR, Reinforcement Learning, Multimodal Models, Datasets]
---
We present X-Decoder, a generalized decoding model that can predict
pixel-level segmentation and language tokens seamlessly. X-Decodert takes as
input two types of queries: (i) generic non-semantic queries and (ii) semantic
queries induced from text inputs, to decode different pixel-level and
token-level outputs in the same semantic space. With such a novel design,
X-Decoder is the first work that provides a unified way to support all types of
image segmentation and a variety of vision-language (VL) tasks. Further, our
design enables seamless interactions across tasks at different granularities
and brings mutual benefits by learning a common and rich pixel-level
visual-semantic understanding space, without any pseudo-labeling. After
pretraining on a mixed set of a limited amount of segmentation data and
millions of image-text pairs, X-Decoder exhibits strong transferability to a
wide range of downstream tasks in both zero-shot and finetuning settings.
Notably, it achieves (1) state-of-the-art results on open-vocabulary
segmentation and referring segmentation on eight datasets; (2) better or
competitive finetuned performance to other generalist and specialist models on
segmentation and VL tasks; and (3) flexibility for efficient finetuning and
novel task composition (e.g., referring captioning and image editing). Code,
demo, video, and visualization are available at https://x-decoder-vl.github.io.