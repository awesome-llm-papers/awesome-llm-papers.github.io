---
layout: publication
title: Identity-preserving Text-to-video Generation Guided By Simple Yet Effective
  Spatial-temporal Decoupled Representations
authors: Wang et al.
conference: Proceedings of the 31st ACM International Conference on Information &amp;
  Knowledge Management
year: 2025
bibkey: wang2025identity
citations: 159
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.04705'}]
tags: [Security, Prompting, Tools, Efficiency And Optimization, Applications, RAG,
  CIKM]
---
Identity-preserving text-to-video (IPT2V) generation, which aims to create high-fidelity videos with consistent human identity, has become crucial for downstream applications. However, current end-to-end frameworks suffer a critical spatial-temporal trade-off: optimizing for spatially coherent layouts of key elements (e.g., character identity preservation) often compromises instruction-compliant temporal smoothness, while prioritizing dynamic realism risks disrupting the spatial coherence of visual structures. To tackle this issue, we propose a simple yet effective spatial-temporal decoupled framework that decomposes representations into spatial features for layouts and temporal features for motion dynamics. Specifically, our paper proposes a semantic prompt optimization mechanism and stage-wise decoupled generation paradigm. The former module decouples the prompt into spatial and temporal components. Aligned with the subsequent stage-wise decoupled approach, the spatial prompts guide the text-to-image (T2I) stage to generate coherent spatial features, while the temporal prompts direct the sequential image-to-video (I2V) stage to ensure motion consistency. Experimental results validate that our approach achieves excellent spatiotemporal consistency, demonstrating outstanding performance in identity preservation, text relevance, and video quality. By leveraging this simple yet robust mechanism, our algorithm secures the runner-up position in 2025 ACM MultiMedia Challenge.