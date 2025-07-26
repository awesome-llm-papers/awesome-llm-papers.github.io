---
layout: publication
title: 'Quartet: Native FP4 Training Can Be Optimal For Large Language Models'
authors: Roberto L. Castro, Andrei Panferov, Soroush Tabesh, Oliver Sieberling, Jiale
  Chen, Mahdi Nikdan, Saleh Ashkboos, Dan Alistarh
conference: No Venue
year: 2025
bibkey: castro2025quartet
additional_links: [{name: Code, url: 'https://github.com/IST-DASLab/Quartet'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/682da9d4781210358218a982'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.14669'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Castro et al.
---
The rapid advancement of large language models (LLMs) has been paralleled by unprecedented increases in computational demands, with training costs for state-of-the-art models doubling every few months. Training models directly in low-precision arithmetic offers a solution, by improving both computational throughput and energy efficiency. Specifically, NVIDIA's recent Blackwell architecture facilitates extremely low-precision operations, specifically FP4 variants, promising substantial efficiency gains. Yet, current algorithms for training LLMs in FP4 precision face significant accuracy degradation and often rely on mixed-precision fallbacks. In this paper, we systematically investigate hardware-supported FP4 training and introduce Quartet, a new approach enabling accurate, end-to-end FP4 training with all the major computations (in e.g. linear layers) being performed in low precision. Through extensive evaluations on Llama-type models, we reveal a new low-precision scaling law that quantifies performance trade-offs across varying bit-widths and allows us to identify a "near-optimal" low-precision training technique in terms of accuracy-vs-computation, called Quartet. We implement Quartet using optimized CUDA kernels tailored for NVIDIA Blackwell GPUs, and show that it can achieve state-of-the-art accuracy for FP4 precision, successfully training billion-scale models. Our method demonstrates that fully FP4-based training is a competitive alternative to standard-precision and FP8 training. Our code is available at https://github.com/IST-DASLab/Quartet.

https://huggingface.co/discussions/paper/682da9d4781210358218a982