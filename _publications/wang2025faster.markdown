---
layout: publication
title: Faster And Better Llms Via Latency-aware Test-time Scaling
authors: Wang et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: wang2025faster
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.19634'}]
tags: [RAG, Reinforcement Learning, Evaluation, Efficiency And Optimization]
---
Test-Time Scaling (TTS) has proven effective in improving the performance of Large Language Models (LLMs) during inference. However, existing research has overlooked the efficiency of TTS from a latency-sensitive perspective. Through a latency-aware evaluation of representative TTS methods, we demonstrate that a compute-optimal TTS does not always result in the lowest latency in scenarios where latency is critical. To address this gap and achieve latency-optimal TTS, we propose two key approaches by optimizing the concurrency configurations: (1) branch-wise parallelism, which leverages multiple concurrent inference branches, and (2) sequence-wise parallelism, enabled by speculative decoding. By integrating these two approaches and allocating computational resources properly to each, our latency-optimal TTS enables a 32B model to reach 82.3% accuracy on MATH-500 within 1 minute and a smaller 3B model to achieve 72.4% within 10 seconds. Our work emphasizes the importance of latency-aware TTS and demonstrates its ability to deliver both speed and accuracy in latency-sensitive scenarios.