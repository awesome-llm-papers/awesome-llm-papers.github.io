---
layout: publication
title: Prompting Visual-language Models For Efficient Video Understanding
authors: Chen Ju, Tengda Han, Kunhao Zheng, Ya Zhang, Weidi Xie
conference: Lecture Notes in Computer Science
year: 2022
bibkey: ju2021prompting
citations: 209
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.04478'}]
tags: ["Prompting"]
short_authors: Ju et al.
---
Image-based visual-language (I-VL) pre-training has shown great success for
learning joint visual-textual representations from large-scale web data,
revealing remarkable ability for zero-shot generalisation. This paper presents
a simple but strong baseline to efficiently adapt the pre-trained I-VL model,
and exploit its powerful ability for resource-hungry video understanding tasks,
with minimal training. Specifically, we propose to optimise a few random
vectors, termed as continuous prompt vectors, that convert video-related tasks
into the same format as the pre-training objectives. In addition, to bridge the
gap between static images and videos, temporal information is encoded with
lightweight Transformers stacking on top of frame-wise visual features.
Experimentally, we conduct extensive ablation studies to analyse the critical
components. On 10 public benchmarks of action recognition, action localisation,
and text-video retrieval, across closed-set, few-shot, and zero-shot scenarios,
we achieve competitive or state-of-the-art performance to existing methods,
despite optimising significantly fewer parameters.