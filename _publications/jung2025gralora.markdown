---
layout: publication
title: 'Gralora: Granular Low-rank Adaptation For Parameter-efficient Fine-tuning'
authors: Yeonjoon Jung, Daehyun Ahn, Hyungjun Kim, Taesu Kim, Eunhyeok Park
conference: No Venue
year: 2025
bibkey: jung2025gralora
additional_links: [{name: Code, url: 'https://github.com/SqueezeBits/GraLoRA.git'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/683674c619543f12e85c4f91'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.20355'}]
tags: ["Fine-Tuning", "Has Code"]
short_authors: Jung et al.
---
Low-Rank Adaptation (LoRA) is a popular method for parameter-efficient fine-tuning (PEFT) of generative models, valued for its simplicity and effectiveness. Despite recent enhancements, LoRA still suffers from a fundamental limitation: overfitting when the bottleneck is widened. It performs best at ranks 32-64, yet its accuracy stagnates or declines at higher ranks, still falling short of full fine-tuning (FFT) performance. We identify the root cause as LoRA's structural bottleneck, which introduces gradient entanglement to the unrelated input channels and distorts gradient propagation. To address this, we introduce a novel structure, Granular Low-Rank Adaptation (GraLoRA) that partitions weight matrices into sub-blocks, each with its own low-rank adapter. With negligible computational or storage cost, GraLoRA overcomes LoRA's limitations, effectively increases the representational capacity, and more closely approximates FFT behavior. Experiments on code generation and commonsense reasoning benchmarks show that GraLoRA consistently outperforms LoRA and other baselines, achieving up to +8.5% absolute gain in Pass@1 on HumanEval+. These improvements hold across model sizes and rank settings, making GraLoRA a scalable and robust solution for PEFT. Code, data, and scripts are available at https://github.com/SqueezeBits/GraLoRA.git

https://huggingface.co/discussions/paper/683674c619543f12e85c4f91