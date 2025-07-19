---
layout: publication
title: Representing Online Handwriting For Recognition In Large Vision-language Models
authors: Fadeeva et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2024
bibkey: fadeeva2024representing
citations: 131
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.15307'}]
tags: [Model Architecture, Fine Tuning, Training Techniques, LLM for Code, Multimodal
    Models, Datasets, Reinforcement Learning]
---
The adoption of tablets with touchscreens and styluses is increasing, and a
key feature is converting handwriting to text, enabling search, indexing, and
AI assistance. Meanwhile, vision-language models (VLMs) are now the go-to
solution for image understanding, thanks to both their state-of-the-art
performance across a variety of tasks and the simplicity of a unified approach
to training, fine-tuning, and inference. While VLMs obtain high performance on
image-based tasks, they perform poorly on handwriting recognition when applied
naively, i.e., by rendering handwriting as an image and performing optical
character recognition (OCR). In this paper, we study online handwriting
recognition with VLMs, going beyond naive OCR. We propose a novel tokenized
representation of digital ink (online handwriting) that includes both a
time-ordered sequence of strokes as text, and as image. We show that this
representation yields results comparable to or better than state-of-the-art
online handwriting recognizers. Wide applicability is shown through results
with two different VLM families, on multiple public datasets. Our approach can
be applied to off-the-shelf VLMs, does not require any changes in their
architecture, and can be used in both fine-tuning and parameter-efficient
tuning. We perform a detailed ablation study to identify the key elements of
the proposed representation.