---
layout: publication
title: 'Mavors: Multi-granularity Video Representation For Multimodal Large Language
  Model'
authors: Yang Shi, Jiaheng Liu, Yushuo Guan, Zhenhua Wu, Yuanxing Zhang, Zihao Wang,
  Weihong Lin, Jingyun Hua, Zekun Wang, Xinlong Chen, Bohan Zeng, Wentao Zhang, Fuzheng
  Zhang, Wenjing Yang, di Zhang
conference: No Venue
year: 2025
bibkey: shi2025mavors
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67fdd1db634e600357b5b8f4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.10068'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Shi et al.
---
Long-context video understanding in multimodal large language models (MLLMs) faces a critical challenge: balancing computational efficiency with the retention of fine-grained spatio-temporal patterns. Existing approaches (e.g., sparse sampling, dense sampling with low resolution, and token compression) suffer from significant information loss in temporal dynamics, spatial details, or subtle interactions, particularly in videos with complex motion or varying resolutions. To address this, we propose Mavors, a novel framework that introduces Multi-granularity video representation for holistic long-video modeling. Specifically, Mavors directly encodes raw video content into latent representations through two core components: 1) an Intra-chunk Vision Encoder (IVE) that preserves high-resolution spatial features via 3D convolutions and Vision Transformers, and 2) an Inter-chunk Feature Aggregator (IFA) that establishes temporal coherence across chunks using transformer-based dependency modeling with chunk-level rotary position encodings. Moreover, the framework unifies image and video understanding by treating images as single-frame videos via sub-image decomposition. Experiments across diverse benchmarks demonstrate Mavors' superiority in maintaining both spatial fidelity and temporal continuity, significantly outperforming existing methods in tasks requiring fine-grained spatio-temporal reasoning.

https://huggingface.co/discussions/paper/67fdd1db634e600357b5b8f4