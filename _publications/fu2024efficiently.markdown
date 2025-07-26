---
layout: publication
title: Efficiently Serving LLM Reasoning Programs With Certaindex
authors: Yichao Fu, Junda Chen, Siqi Zhu, Zheyu Fu, Zhongdongming Dai, Aurick Qiao,
  Hao Zhang
conference: No Venue
year: 2024
bibkey: fu2024efficiently
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6773560bd86f2a71877259f6'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.20993'}]
tags: ["Datasets", "Llm For Code"]
short_authors: Fu et al.
---
The rapid evolution of large language models (LLMs) has unlocked their capabilities in advanced reasoning tasks like mathematical problem-solving, code generation, and legal analysis. Central to this progress are inference-time reasoning algorithms, which refine outputs by exploring multiple solution paths, at the cost of increasing compute demands and response latencies. Existing serving systems fail to adapt to the scaling behaviors of these algorithms or the varying difficulty of queries, leading to inefficient resource use and unmet latency targets. We present Dynasor, a system that optimizes inference-time compute for LLM reasoning queries. Unlike traditional engines, Dynasor tracks and schedules requests within reasoning queries and uses Certaindex, a proxy that measures statistical reasoning progress based on model certainty, to guide compute allocation dynamically. Dynasor co-adapts scheduling with reasoning progress: it allocates more compute to hard queries, reduces compute for simpler ones, and terminates unpromising queries early, balancing accuracy, latency, and cost. On diverse datasets and algorithms, Dynasor reduces compute by up to 50% in batch processing and sustaining 3.3x higher query rates or 4.7x tighter latency SLOs in online serving.

https://huggingface.co/discussions/paper/6773560bd86f2a71877259f6