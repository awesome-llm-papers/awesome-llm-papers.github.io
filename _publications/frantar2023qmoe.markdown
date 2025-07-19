---
layout: publication
title: 'Qmoe: Practical Sub-1-bit Compression Of Trillion-parameter Models'
authors: Frantar Elias, Alistarh Dan
conference: 'SC20: International Conference for High Performance Computing, Networking,
  Storage and Analysis'
year: 2023
bibkey: frantar2023qmoe
citations: 361
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.16795'}]
tags: [Model Architecture, Distillation, Tools, Pre-Training, RAG, Transformer]
---
Mixture-of-Experts (MoE) architectures offer a general solution to the high
inference costs of large language models (LLMs) via sparse routing, bringing
faster and more accurate models, at the cost of massive parameter counts. For
example, the SwitchTransformer-c2048 model has 1.6 trillion parameters,
requiring 3.2TB of accelerator memory to run efficiently, which makes practical
deployment challenging and expensive. In this paper, we present a solution to
this memory problem, in form of a new compression and execution framework
called QMoE. Specifically, QMoE consists of a scalable algorithm which
accurately compresses trillion-parameter MoEs to less than 1 bit per parameter,
in a custom format co-designed with bespoke GPU decoding kernels to facilitate
efficient end-to-end compressed inference, with minor runtime overheads
relative to uncompressed execution. Concretely, QMoE can compress the 1.6
trillion parameter SwitchTransformer-c2048 model to less than 160GB (20x
compression, 0.8 bits per parameter) at only minor accuracy loss, in less than
a day on a single GPU. This enables, for the first time, the execution of a
trillion-parameter model on affordable commodity hardware, like a single server
with 4x NVIDIA A6000 or 8x NVIDIA 3090 GPUs, at less than 5% runtime overhead
relative to ideal uncompressed inference. The source code and compressed models
are available at github.com/IST-DASLab/qmoe.