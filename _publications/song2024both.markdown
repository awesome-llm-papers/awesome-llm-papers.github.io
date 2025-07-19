---
layout: publication
title: Both Text And Images Leaked! A Systematic Analysis Of Multimodal LLM Data Contamination
authors: Song et al.
conference: Pattern Recognition
year: 2024
bibkey: song2024both
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.03823'}]
tags: [Training Techniques, Tools, CVPR, Evaluation, Multimodal Models, Datasets]
---
The rapid progression of multimodal large language models (MLLMs) has
demonstrated superior performance on various multimodal benchmarks. However,
the issue of data contamination during training creates challenges in
performance evaluation and comparison. While numerous methods exist for
detecting models' contamination in large language models (LLMs), they are less
effective for MLLMs due to their various modalities and multiple training
phases. In this study, we introduce a multimodal data contamination detection
framework, MM-Detect, designed for MLLMs. Our experimental results indicate
that MM-Detect is quite effective and sensitive in identifying varying degrees
of contamination, and can highlight significant performance improvements due to
the leakage of multimodal benchmark training sets. Furthermore, we explore
whether the contamination originates from the base LLMs used by MLLMs or the
multimodal training phase, providing new insights into the stages at which
contamination may be introduced.