---
layout: publication
title: 'Softpick: No Attention Sink, No Massive Activations With Rectified Softmax'
authors: Zayd M. K. Zuhri, Erland Hilman Fuadi, Alham Fikri Aji
conference: No Venue
year: 2025
bibkey: zuhri2025softpick
additional_links: [{name: Code, url: 'https://github.com/zaydzuhri/softpick-attention'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6812e475060494e99e4c519f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.20966'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Zayd M. K. Zuhri, Erland Hilman Fuadi, Alham Fikri Aji
---
We introduce softpick, a rectified, not sum-to-one, drop-in replacement for softmax in transformer attention mechanisms that eliminates attention sink and massive activations. Our experiments with 340M parameter models demonstrate that softpick maintains performance parity with softmax on standard benchmarks while achieving 0% sink rate. The softpick transformer produces hidden states with significantly lower kurtosis (340 vs 33,510) and creates sparse attention maps (46.97% sparsity). Models using softpick consistently outperform softmax when quantized, with particularly pronounced advantages at lower bit precisions. Our analysis and discussion shows how softpick has the potential to open new possibilities for quantization, low-precision training, sparsity optimization, pruning, and interpretability. Our code is available at https://github.com/zaydzuhri/softpick-attention.

https://huggingface.co/discussions/paper/6812e475060494e99e4c519f