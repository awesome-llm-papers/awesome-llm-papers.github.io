---
layout: publication
title: 'Smoothrot: Combining Channel-wise Scaling And Rotation For Quantization-friendly
  Llms'
authors: "Czak\xF3 Patrik, Kert\xE9sz G\xE1bor, Sz\xE9n\xE1si S\xE1ndor"
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: "czak\xF32025smoothrot"
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.05413'}]
tags: [CVPR, Efficiency And Optimization, Quantization, Training Techniques]
---
We present SmoothRot, a novel post-training quantization technique to enhance the efficiency of 4-bit quantization in Large Language Models (LLMs). SmoothRot addresses the critical challenge of massive activation outliers, by integrating channel-wise scaling with Hadamard transformations. Our technique effectively transforms extreme outliers into quantization-friendly activations, significantly improving quantization accuracy. Experiments conducted on popular LLMs (LLaMA2 7B, LLaMA3.1 8B, and Mistral 7B) demonstrate that SmoothRot consistently reduces the performance gap between quantized and FP16 models by approximately 10-30% across language generation and zero-shot reasoning tasks, without introducing additional inference latency. Code is available at https://github.com/czakop/smoothrot.