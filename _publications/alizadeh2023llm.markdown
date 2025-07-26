---
layout: publication
title: 'LLM In A Flash: Efficient Large Language Model Inference With Limited Memory'
authors: Keivan Alizadeh, Iman Mirzadeh, Dmitry Belenko, Karen Khatamifard, Minsik
  Cho, Carlo C del Mundo, Mohammad Rastegari, Mehrdad Farajtabar
conference: No Venue
year: 2023
bibkey: alizadeh2023llm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2312.11514'}]
tags: ["Tools"]
short_authors: Alizadeh et al.
---
Large language models (LLMs) are central to modern natural language processing, delivering exceptional performance in various tasks. However, their intensive computational and memory requirements present challenges, especially for devices with limited DRAM capacity. This paper tackles the challenge of efficiently running LLMs that exceed the available DRAM capacity by storing the model parameters on flash memory but bringing them on demand to DRAM. Our method involves constructing an inference cost model that harmonizes with the flash memory behavior, guiding us to optimize in two critical areas: reducing the volume of data transferred from flash and reading data in larger, more contiguous chunks. Within this flash memory-informed framework, we introduce two principal techniques. First, "windowing'" strategically reduces data transfer by reusing previously activated neurons, and second, "row-column bundling", tailored to the sequential data access strengths of flash memory, increases the size of data chunks read from flash memory. These methods collectively enable running models up to twice the size of the available DRAM, with a 4-5x and 20-25x increase in inference speed compared to naive loading approaches in CPU and GPU, respectively. Our integration of sparsity awareness, context-adaptive loading, and a hardware-oriented design paves the way for effective inference of LLMs on devices with limited memory.

https://huggingface.co/discussions/paper/6582524b5f6d8343825e4b13