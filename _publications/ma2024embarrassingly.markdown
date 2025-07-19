---
layout: publication
title: An Embarrassingly Simple Approach For LLM With Strong ASR Capacity
authors: Ma et al.
conference: Advances in Computer Vision and Pattern Recognition
year: 2024
bibkey: ma2024embarrassingly
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.08846'}]
tags: [Training Techniques, CVPR, Evaluation, Fine Tuning, Multimodal Models, Datasets]
---
In this paper, we focus on solving one of the most important tasks in the
field of speech processing, i.e., automatic speech recognition (ASR), with
speech foundation encoders and large language models (LLM). Recent works have
complex designs such as compressing the output temporally for the speech
encoder, tackling modal alignment for the projector, and utilizing
parameter-efficient fine-tuning for the LLM. We found that delicate designs are
not necessary, while an embarrassingly simple composition of off-the-shelf
speech encoder, LLM, and the only trainable linear projector is competent for
the ASR task. To be more specific, we benchmark and explore various
combinations of LLMs and speech encoders, leading to the optimal LLM-based ASR
system, which we call SLAM-ASR. The proposed SLAM-ASR provides a clean setup
and little task-specific design, where only the linear projector is trained. To
the best of our knowledge, SLAM-ASR achieves the best performance on the
Librispeech benchmark among LLM-based ASR models and even outperforms the
latest LLM-based audio-universal model trained on massive pair data. Finally,
we explore the capability emergence of LLM-based ASR in the process of modal
alignment. We hope that our study can facilitate the research on extending LLM
with cross-modality capacity and shed light on the LLM-based ASR community.