---
layout: publication
title: 'Powerinfer: Fast Large Language Model Serving With A Consumer-grade GPU'
authors: Yixin Song, Zeyu Mi, Haotong Xie, Haibo Chen
conference: No Venue
year: 2023
bibkey: song2023powerinfer
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2312.12456'}]
tags: ["Efficiency", "Tools"]
short_authors: Song et al.
---
This paper introduces PowerInfer, a high-speed Large Language Model (LLM) inference engine on a personal computer (PC) equipped with a single consumer-grade GPU. The key underlying the design of PowerInfer is exploiting the high locality inherent in LLM inference, characterized by a power-law distribution in neuron activation. This distribution indicates that a small subset of neurons, termed hot neurons, are consistently activated across inputs, while the majority, cold neurons, vary based on specific inputs. PowerInfer exploits such an insight to design a GPU-CPU hybrid inference engine: hot-activated neurons are preloaded onto the GPU for fast access, while cold-activated neurons are computed on the CPU, thus significantly reducing GPU memory demands and CPU-GPU data transfers. PowerInfer further integrates adaptive predictors and neuron-aware sparse operators, optimizing the efficiency of neuron activation and computational sparsity. Evaluation shows that PowerInfer attains an average token generation rate of 13.20 tokens/s, with a peak of 29.08 tokens/s, across various LLMs (including OPT-175B) on a single NVIDIA RTX 4090 GPU, only 18% lower than that achieved by a top-tier server-grade A100 GPU. This significantly outperforms llama.cpp by up to 11.69x while retaining model accuracy.

https://huggingface.co/discussions/paper/6583b15a1804c2d060ac9e87