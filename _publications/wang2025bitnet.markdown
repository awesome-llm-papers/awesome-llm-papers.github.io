---
layout: publication
title: 'Bitnet V2: Native 4-bit Activations With Hadamard Transformation For 1-bit
  Llms'
authors: Hongyu Wang, Shuming Ma, Furu Wei
conference: No Venue
year: 2025
bibkey: wang2025bitnet
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.18415'}]
tags: ["Efficiency"]
short_authors: Hongyu Wang, Shuming Ma, Furu Wei
---
Efficient deployment of 1-bit Large Language Models (LLMs) is hindered by activation outliers, which complicate quantization to low bit-widths. We introduce BitNet v2, a novel framework enabling native 4-bit activation quantization for 1-bit LLMs. To tackle outliers in attention and feed-forward network activations, we propose H-BitLinear, a module applying an online Hadamard transformation prior to activation quantization. This transformation smooths sharp activation distributions into more Gaussian-like forms, suitable for low-bit representation. Experiments show BitNet v2 trained from scratch with 8-bit activations matches BitNet b1.58 performance. Crucially, BitNet v2 achieves minimal performance degradation when trained with native 4-bit activations, significantly reducing memory footprint and computational cost for batched inference.

https://huggingface.co/discussions/paper/680ef1559cc294f617fb1536