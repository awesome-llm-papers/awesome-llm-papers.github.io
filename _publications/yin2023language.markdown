---
layout: publication
title: 'LAMM: Language-assisted Multi-modal Instruction-tuning Dataset, Framework,
  And Benchmark'
authors: Zhenfei Yin et al.
conference: Arxiv
year: 2023
citations: 23
bibkey: yin2023language
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.06687'}]
tags: [Model Architecture, Ethics and Bias, GPT, Fine-Tuning, Tools, Reinforcement
    Learning, Agentic, Training Techniques, Evaluation]
---
Large language models have emerged as a promising approach towards achieving
general-purpose AI agents. The thriving open-source LLM community has greatly
accelerated the development of agents that support human-machine dialogue
interaction through natural language processing. However, human interaction
with the world extends beyond only text as a modality, and other modalities
such as vision are also crucial. Recent works on multi-modal large language
models, such as GPT-4V and Bard, have demonstrated their effectiveness in
handling visual modalities. However, the transparency of these works is limited
and insufficient to support academic research. To the best of our knowledge, we
present one of the very first open-source endeavors in the field, LAMM,
encompassing a Language-Assisted Multi-Modal instruction tuning dataset,
framework, and benchmark. Our aim is to establish LAMM as a growing ecosystem
for training and evaluating MLLMs, with a specific focus on facilitating AI
agents capable of bridging the gap between ideas and execution, thereby
enabling seamless human-AI interaction. Our main contribution is three-fold: 1)
We present a comprehensive dataset and benchmark, which cover a wide range of
vision tasks for 2D and 3D vision. Extensive experiments validate the
effectiveness of our dataset and benchmark. 2) We outline the detailed
methodology of constructing multi-modal instruction tuning datasets and
benchmarks for MLLMs, enabling rapid scaling and extension of MLLM research to
diverse domains, tasks, and modalities. 3) We provide a primary but potential
MLLM training framework optimized for modality extension. We also provide
baseline models, comprehensive experimental observations, and analysis to
accelerate future research. Our baseline model is trained within 24 A100 GPU
hours, framework supports training with V100 and RTX3090 is available thanks to
the open-source society.