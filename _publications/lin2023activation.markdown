---
layout: publication
title: 'AWQ: Activation-aware Weight Quantization For LLM Compression And Acceleration'
authors: Ji Lin et al.
conference: 'GetMobile: Mobile Computing and Communications'
year: 2023
citations: 21
bibkey: lin2023activation
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.00978'}]
tags: [Language Modeling, Applications, Quantization, Tools, Efficiency and Optimization,
  Evaluation, Merging]
---
Large language models (LLMs) have transformed numerous AI applications.
On-device LLM is becoming increasingly important: running LLMs locally on edge
devices can reduce the cloud computing cost and protect users' privacy.
However, the astronomical model size and the limited hardware resource pose
significant deployment challenges. We propose Activation-aware Weight
Quantization (AWQ), a hardware-friendly approach for LLM low-bit weight-only
quantization. AWQ finds that not all weights in an LLM are equally important.
Protecting only 1% salient weights can greatly reduce quantization error. To
identify salient weight channels, we should refer to the activation
distribution, not weights. To avoid the hardware-inefficient mix-precision
quantization, we mathematically derive that scaling up the salient channels can
reduce the quantization error. AWQ employs an equivalent transformation to
scale the salient weight channels to protect them. The scale is determined by
collecting the activation statistics offline. AWQ does not rely on any
backpropagation or reconstruction, so it generalizes to different domains and
modalities without overfitting the calibration set. AWQ outperforms existing
work on various language modeling and domain-specific benchmarks (coding and
math). Thanks to better generalization, it achieves excellent quantization
performance for instruction-tuned LMs and, for the first time, multi-modal LMs.
Alongside AWQ, we implement TinyChat, an efficient and flexible inference
framework tailored for 4-bit on-device LLM/VLMs. With kernel fusion and
platform-aware weight packing, TinyChat offers more than 3x speedup over the
Huggingface FP16 implementation on both desktop and mobile GPUs. It also
democratizes the deployment of the 70B Llama-2 model on mobile GPUs.