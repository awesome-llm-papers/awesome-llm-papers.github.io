---
layout: publication
title: 'TPI-LLM: Serving 70b-scale Llms Efficiently On Low-resource Edge Devices'
authors: Zonghang Li, Wenjiao Feng, Mohsen Guizani, Hongfang Yu
conference: No Venue
year: 2024
bibkey: li2024tpi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.00531'}]
tags: ["Memory & Context", "Privacy"]
short_authors: Li et al.
---
Large model inference is shifting from cloud to edge due to concerns about the privacy of user interaction data. However, edge devices often struggle with limited computing power, memory, and bandwidth, requiring collaboration across multiple devices to run and speed up LLM inference. Pipeline parallelism, the mainstream solution, is inefficient for single-user scenarios, while tensor parallelism struggles with frequent communications. In this paper, we argue that tensor parallelism can be more effective than pipeline on low-resource devices, and present a compute- and memory-efficient tensor parallel inference system, named TPI-LLM, to serve 70B-scale models. TPI-LLM keeps sensitive raw data local in the users' devices and introduces a sliding window memory scheduler to dynamically manage layer weights during inference, with disk I/O latency overlapped with the computation and communication. This allows larger models to run smoothly on memory-limited devices. We analyze the communication bottleneck and find that link latency, not bandwidth, emerges as the main issue, so a star-based allreduce algorithm is implemented. Through extensive experiments on both emulated and real testbeds, TPI-LLM demonstrated over 80% less time-to-first-token and token latency compared to Accelerate, and over 90% compared to Transformers and Galaxy, while cutting the peak memory footprint of Llama 2-70B by 90%, requiring only 3.1 GB of memory for 70B-scale models.

https://huggingface.co/discussions/paper/66fcb61de97377a6e456c263