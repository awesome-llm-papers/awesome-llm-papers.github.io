---
layout: publication
title: 'FUSION: Fully Integration Of Vision-language Representations For Deep Cross-modal
  Understanding'
authors: Zheng Liu, Mengjie Liu, Jingzhou Chen, Jingwei Xu, Bin Cui, Conghui He, Wentao
  Zhang
conference: No Venue
year: 2025
bibkey: liu2025fusion
additional_links: [{name: Code, url: 'https://github.com/starriver030515/FUSION'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67fdb5f3913c97aa32f13141'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.09925'}]
tags: ["Has Code"]
short_authors: Liu et al.
---
We introduce FUSION, a family of multimodal large language models (MLLMs) with a fully vision-language alignment and integration paradigm. Unlike existing methods that primarily rely on late-stage modality interaction during LLM decoding, our approach achieves deep, dynamic integration throughout the entire processing pipeline. To this end, we propose Text-Guided Unified Vision Encoding, incorporating textual information in vision encoding to achieve pixel-level integration. We further design Context-Aware Recursive Alignment Decoding that recursively aggregates visual features conditioned on textual context during decoding, enabling fine-grained, question-level semantic integration. To guide feature mapping and mitigate modality discrepancies, we develop Dual-Supervised Semantic Mapping Loss. Additionally, we construct a Synthesized Language-Driven Question-Answer (QA) dataset through a new data synthesis method, prioritizing high-quality QA pairs to optimize text-guided feature integration. Building on these foundations, we train FUSION at two scales-3B, 8B-and demonstrate that our full-modality integration approach significantly outperforms existing methods with only 630 vision tokens. Notably, FUSION 3B surpasses Cambrian-1 8B and Florence-VL 8B on most benchmarks. FUSION 3B continues to outperform Cambrian-1 8B even when limited to 300 vision tokens. Our ablation studies show that FUSION outperforms LLaVA-NeXT on over half of the benchmarks under same configuration without dynamic resolution, highlighting the effectiveness of our approach. We release our code, model weights, and dataset. https://github.com/starriver030515/FUSION

https://huggingface.co/discussions/paper/67fdb5f3913c97aa32f13141