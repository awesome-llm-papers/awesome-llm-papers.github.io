---
layout: publication
title: 'Billm: Pushing The Limit Of Post-training Quantization For Llms'
authors: Wei Huang et al.
conference: Arxiv
year: 2024
citations: 16
bibkey: huang2024pushing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.04291'}, {name: Code,
    url: 'https://github.com/Aaronhuang-778/BiLLM'}]
tags: [Has Code, Quantization, Efficiency and Optimization, Training Techniques, Evaluation]
---
Pretrained large language models (LLMs) exhibit exceptional general language
processing capabilities but come with significant demands on memory and
computational resources. As a powerful compression technology, binarization can
extremely reduce model weights to a mere 1 bit, lowering the expensive
computation and memory requirements. However, existing quantization techniques
fall short of maintaining LLM performance under ultra-low bit-widths. In
response to this challenge, we present BiLLM, a groundbreaking 1-bit
post-training quantization scheme tailored for pretrained LLMs. Based on the
weight distribution of LLMs, BiLLM first identifies and structurally selects
salient weights, and minimizes the compression loss through an effective binary
residual approximation strategy. Moreover, considering the bell-shaped
distribution of the non-salient weights, we propose an optimal splitting search
to group and binarize them accurately. BiLLM achieving for the first time
high-accuracy inference (e.g. 8.41 perplexity on LLaMA2-70B) with only 1.08-bit
weights across various LLMs families and evaluation metrics, outperforms SOTA
quantization methods of LLM by significant margins. Moreover, BiLLM enables the
binarization process of the LLM with 7 billion weights within 0.5 hours on a
single GPU, demonstrating satisfactory time efficiency. Our code is available
at https://github.com/Aaronhuang-778/BiLLM.