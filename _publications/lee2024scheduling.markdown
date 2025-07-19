---
layout: publication
title: Scheduling Weight Transitions For Quantization-aware Training
authors: Lee et al.
conference: Machine Learning
year: 2024
bibkey: lee2024scheduling
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.19248'}]
tags: [Training Techniques, Evaluation, ICML, Efficiency And Optimization, Quantization,
  Datasets]
---
Quantization-aware training (QAT) simulates a quantization process during
training to lower bit-precision of weights/activations. It learns quantized
weights indirectly by updating latent weights,i.e., full-precision inputs to a
quantizer, using gradient-based optimizers. We claim that coupling a
user-defined learning rate (LR) with these optimizers is sub-optimal for QAT.
Quantized weights transit discrete levels of a quantizer, only if corresponding
latent weights pass transition points, where the quantizer changes discrete
states. This suggests that the changes of quantized weights are affected by
both the LR for latent weights and their distributions. It is thus difficult to
control the degree of changes for quantized weights by scheduling the LR
manually. We conjecture that the degree of parameter changes in QAT is related
to the number of quantized weights transiting discrete levels. Based on this,
we introduce a transition rate (TR) scheduling technique that controls the
number of transitions of quantized weights explicitly. Instead of scheduling a
LR for latent weights, we schedule a target TR of quantized weights, and update
the latent weights with a novel transition-adaptive LR (TALR), enabling
considering the degree of changes for the quantized weights during QAT.
Experimental results demonstrate the effectiveness of our approach on standard
benchmarks.