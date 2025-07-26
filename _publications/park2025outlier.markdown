---
layout: publication
title: Outlier-safe Pre-training For Robust 4-bit Quantization Of Large Language Models
authors: Jungwoo Park, Taewhoo Lee, Chanwoong Yoon, Hyeon Hwang, Jaewoo Kang
conference: No Venue
year: 2025
bibkey: park2025outlier
additional_links: [{name: Code, url: 'https://github.com/dmis-lab/Outlier-Safe-Pre-Training'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/685c1546df8a0d6c70bbf953'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.19697'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Park et al.
---
Extreme activation outliers in Large Language Models (LLMs) critically degrade quantization performance, hindering efficient on-device deployment. While channel-wise operations and adaptive gradient scaling are recognized causes, practical mitigation remains challenging. We introduce Outlier-Safe Pre-Training (OSP), a practical guideline that proactively prevents outlier formation rather than relying on post-hoc mitigation. OSP combines three key innovations: (1) the Muon optimizer, eliminating privileged bases while maintaining training efficiency; (2) Single-Scale RMSNorm, preventing channel-wise amplification; and (3) a learnable embedding projection, redistributing activation magnitudes originating from embedding matrices. We validate OSP by training a 1.4B-parameter model on 1 trillion tokens, which is the first production-scale LLM trained without such outliers. Under aggressive 4-bit quantization, our OSP model achieves a 35.7 average score across 10 benchmarks (compared to 26.5 for an Adam-trained model), with only a 2% training overhead. Remarkably, OSP models exhibit near-zero excess kurtosis (0.04) compared to extreme values (1818.56) in standard models, fundamentally altering LLM quantization behavior. Our work demonstrates that outliers are not inherent to LLMs but are consequences of training strategies, paving the way for more efficient LLM deployment. The source code and pretrained checkpoints are available at https://github.com/dmis-lab/Outlier-Safe-Pre-Training.

https://huggingface.co/discussions/paper/685c1546df8a0d6c70bbf953