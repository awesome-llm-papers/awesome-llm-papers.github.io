---
layout: publication
title: Chatgpt Or Grammarly? Evaluating Chatgpt On Grammatical Error Correction Benchmark
authors: Haoran Wu, Wenxuan Wang, Yuxuan Wan, Wenxiang Jiao, Michael Lyu
conference: Arxiv
year: 2023
citations: 40
bibkey: wu2023chatgpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.13648'}]
tags: [Reinforcement Learning, Attention Mechanism, Model Architecture, GPT]
---
ChatGPT is a cutting-edge artificial intelligence language model developed by
OpenAI, which has attracted a lot of attention due to its surprisingly strong
ability in answering follow-up questions. In this report, we aim to evaluate
ChatGPT on the Grammatical Error Correction(GEC) task, and compare it with
commercial GEC product (e.g., Grammarly) and state-of-the-art models (e.g.,
GECToR). By testing on the CoNLL2014 benchmark dataset, we find that ChatGPT
performs not as well as those baselines in terms of the automatic evaluation
metrics (e.g., \\(F_\{0.5\}\\) score), particularly on long sentences. We inspect the
outputs and find that ChatGPT goes beyond one-by-one corrections. Specifically,
it prefers to change the surface expression of certain phrases or sentence
structure while maintaining grammatical correctness. Human evaluation
quantitatively confirms this and suggests that ChatGPT produces less
under-correction or mis-correction issues but more over-corrections. These
results demonstrate that ChatGPT is severely under-estimated by the automatic
evaluation metrics and could be a promising tool for GEC.