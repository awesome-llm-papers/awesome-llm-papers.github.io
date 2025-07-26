---
layout: publication
title: 'Quickvideo: Real-time Long Video Understanding With System Algorithm Co-design'
authors: Benjamin Schneider, Dongfu Jiang, Chao Du, Tianyu Pang, Wenhu Chen
conference: No Venue
year: 2025
bibkey: schneider2025quickvideo
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/682fd91b1ffb93faf139d2d0'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.16175'}]
tags: ["Applications", "Efficiency"]
short_authors: Schneider et al.
---
Long-video understanding has emerged as a crucial capability in real-world applications such as video surveillance, meeting summarization, educational lecture analysis, and sports broadcasting. However, it remains computationally prohibitive for VideoLLMs, primarily due to two bottlenecks: 1) sequential video decoding, the process of converting the raw bit stream to RGB frames can take up to a minute for hour-long video inputs, and 2) costly prefilling of up to several million tokens for LLM inference, resulting in high latency and memory use. To address these challenges, we propose QuickVideo, a system-algorithm co-design that substantially accelerates long-video understanding to support real-time downstream applications. It comprises three key innovations: QuickDecoder, a parallelized CPU-based video decoder that achieves 2-3 times speedup by splitting videos into keyframe-aligned intervals processed concurrently; QuickPrefill, a memory-efficient prefilling method using KV-cache pruning to support more frames with less GPU memory; and an overlapping scheme that overlaps CPU video decoding with GPU inference. Together, these components infernece time reduce by a minute on long video inputs, enabling scalable, high-quality video understanding even on limited hardware. Experiments show that QuickVideo generalizes across durations and sampling rates, making long video processing feasible in practice.

https://huggingface.co/discussions/paper/682fd91b1ffb93faf139d2d0