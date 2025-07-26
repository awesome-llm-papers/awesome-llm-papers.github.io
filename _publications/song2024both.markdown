---
layout: publication
title: Both Text And Images Leaked! A Systematic Analysis Of Multimodal LLM Data Contamination
authors: Dingjie Song, Sicheng Lai, Shunian Chen, Lichao Sun, Benyou Wang
conference: No Venue
year: 2024
bibkey: song2024both
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.03823'}]
tags: ["Datasets", "Evaluation"]
short_authors: Song et al.
---
The rapid progression of multimodal large language models (MLLMs) has demonstrated superior performance on various multimodal benchmarks. However, the issue of data contamination during training creates challenges in performance evaluation and comparison. While numerous methods exist for detecting dataset contamination in large language models (LLMs), they are less effective for MLLMs due to their various modalities and multiple training phases. In this study, we introduce a multimodal data contamination detection framework, MM-Detect, designed for MLLMs. Our experimental results indicate that MM-Detect is sensitive to varying degrees of contamination and can highlight significant performance improvements due to leakage of the training set of multimodal benchmarks. Furthermore, We also explore the possibility of contamination originating from the pre-training phase of LLMs used by MLLMs and the fine-tuning phase of MLLMs, offering new insights into the stages at which contamination may be introduced.

https://huggingface.co/discussions/paper/672c2ca8dbc16559ba1d8fd1