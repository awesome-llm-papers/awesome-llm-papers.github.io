---
layout: publication
title: 'DAQ: Density-aware Post-training Weight-only Quantization For Llms'
authors: Luo Yingsong, Chen Ling
conference: Machine Learning
year: 2024
bibkey: luo2024daq
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.12187'}]
tags: [RAG, Training Techniques, ICML, Efficiency And Optimization, Quantization]
---
Large language models (LLMs) excel in various tasks but face deployment
challenges due to hardware constraints. We propose density-aware post-training
weight-only quantization (DAQ), which has two stages: 1) density-centric
alignment, which identifies the center of high-density weights and centers the
dynamic range on this point to align high-density weight regions with
floating-point high-precision regions; 2) learnable dynamic range adjustment,
which adjusts the dynamic range by optimizing quantization parameters (i.e.,
scale and zero-point) based on the impact of weights on the model output.
Experiments on LLaMA and LLaMA-2 show that DAQ consistently outperforms the
best baseline method, reducing perplexity loss by an average of 22.8% on LLaMA
and 19.6% on LLaMA-2. Our code is available at
https://github.com/LuoYingSong/DAQ.