---
layout: publication
title: 'GOBO: Quantizing Attention-based NLP Models For Low Latency And Energy Efficient
  Inference'
authors: Ali Hadi Zadeh, Isak Edo, Omar Mohamed Awad, Andreas Moshovos
conference: 2020 53rd Annual IEEE/ACM International Symposium on Microarchitecture
  (MICRO)
year: 2020
bibkey: zadeh2020gobo
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.03842'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Zadeh et al.
---
Attention-based models have demonstrated remarkable success in various
natural language understanding tasks. However, efficient execution remains a
challenge for these models which are memory-bound due to their massive number
of parameters. We present GOBO, a model quantization technique that compresses
the vast majority (typically 99.9%) of the 32-bit floating-point parameters of
state-of-the-art BERT models and their variants to 3 bits while maintaining
their accuracy. Unlike other quantization methods, GOBO does not require
fine-tuning nor retraining to compensate for the quantization error. We present
two practical hardware applications of GOBO. In the first GOBO reduces memory
storage and traffic and as a result inference latency and energy consumption.
This GOBO memory compression mechanism is plug-in compatible with many
architectures; we demonstrate it with the TPU, Eyeriss, and an architecture
using Tensor Cores-like units. Second, we present a co-designed hardware
architecture that also reduces computation. Uniquely, the GOBO architecture
maintains most of the weights in 3b even during computation, a property that:
(1) makes the processing elements area efficient, allowing us to pack more
compute power per unit area, (2) replaces most multiply-accumulations with
additions, and (3) reduces the off-chip traffic by amplifying on-chip memory
capacity.