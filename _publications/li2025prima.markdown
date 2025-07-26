---
layout: publication
title: 'PRIMA.CPP: Speeding Up 70b-scale LLM Inference On Low-resource Everyday Home
  Clusters'
authors: Zonghang Li, Tao Li, Wenjiao Feng, Mohsen Guizani, Hongfang Yu
conference: No Venue
year: 2025
bibkey: li2025prima
additional_links: [{name: Code, url: 'https://github.com/Lizonghang/prima.cpp'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/67fdbdeb64a418633ee9fb58'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.08791'}]
tags: ["Efficiency", "Has Code", "Tools"]
short_authors: Li et al.
---
Emergency of DeepSeek R1 and QwQ 32B have broken through performance barriers for running frontier large language models (LLMs) on home devices. While consumer hardware is getting stronger and model quantization is improving, existing end-side solutions still demand GPU clusters, large RAM/VRAM, and high bandwidth, far beyond what a common home cluster can handle. This paper introduces prima.cpp, a distributed inference system that runs 70B-scale models on everyday home devices using a mix of CPU/GPU, low RAM/VRAM, Wi-Fi, and cross-platform support. It uses mmap to manage model weights and introduces piped-ring parallelism with prefetching to hide disk loading. By modeling heterogeneity in computation, communication, disk, memory (and its management behavior), and OS, it optimally assigns model layers to each device's CPU and GPU, further reducing token latency. An elegant algorithm named Halda is proposed to solve this NP-hard assignment problem. We evaluate prima.cpp on a common four-node home cluster. It outperforms llama.cpp, exo, and dllama on 30B+ models while keeping memory pressure below 6%. This brings frontier 30B-70B models, such as Llama 3, DeepSeek R1, Qwen 2.5, and QwQ to home assistants, making advanced AI truly accessible to individuals. The code is open source and available at https://github.com/Lizonghang/prima.cpp.

https://huggingface.co/discussions/paper/67fdbdeb64a418633ee9fb58