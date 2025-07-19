---
layout: publication
title: 'Text Generation With Diffusion Language Models: A Pre-training Approach With
  Continuous Paragraph Denoise'
authors: Lin et al.
conference: ACM Computing Surveys
year: 2022
bibkey: lin2022text
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.11685'}]
tags: [RAG, Training Techniques, GPT, Tools, Evaluation, Survey Paper, Language Modeling,
  Datasets, Merging]
---
In this paper, we introduce a novel dIffusion language modEl pre-training
framework for text generation, which we call GENIE. GENIE is a large-scale
pretrained diffusion language model that consists of an encoder and a
diffusion-based decoder, which can generate text by gradually transforming a
random noise sequence into a coherent text sequence. To pre-train GENIE on a
large-scale language corpus, we design a new continuous paragraph denoise
objective, which encourages the diffusion-decoder to reconstruct a clean text
paragraph from a corrupted version, while preserving the semantic and syntactic
coherence. We evaluate GENIE on four downstream text generation benchmarks,
namely XSum, CNN/DailyMail, Gigaword, and CommonGen. Our experimental results
show that GENIE achieves comparable performance with the state-of-the-art
autoregressive models on these benchmarks, and generates more diverse text
samples. The code and models of GENIE are available at
https://github.com/microsoft/ProphetNet/tree/master/GENIE.