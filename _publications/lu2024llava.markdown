---
layout: publication
title: 'Llava-mr: Large Language-and-vision Assistant For Video Moment Retrieval'
authors: Weiheng Lu et al.
conference: Arxiv
year: 2024
citations: 36
bibkey: lu2024llava
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.14505'}]
tags: [Multimodal Models]
---
Multimodal Large Language Models (MLLMs) are widely used for visual
perception, understanding, and reasoning. However, long video processing and
precise moment retrieval remain challenging due to LLMs' limited context size
and coarse frame extraction. We propose the Large Language-and-Vision Assistant
for Moment Retrieval (LLaVA-MR), which enables accurate moment retrieval and
contextual grounding in videos using MLLMs. LLaVA-MR combines Dense Frame and
Time Encoding (DFTE) for spatial-temporal feature extraction, Informative Frame
Selection (IFS) for capturing brief visual and motion patterns, and Dynamic
Token Compression (DTC) to manage LLM context limitations. Evaluations on
benchmarks like Charades-STA and QVHighlights demonstrate that LLaVA-MR
outperforms 11 state-of-the-art methods, achieving an improvement of 1.82% in
R1@0.5 and 1.29% in mAP@0.5 on the QVHighlights dataset. Our implementation
will be open-sourced upon acceptance.