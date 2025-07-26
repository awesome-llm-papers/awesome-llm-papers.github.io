---
layout: publication
title: 'Fourier Position Embedding: Enhancing Attention''s Periodic Extension For
  Length Generalization'
authors: Ermo Hua, Che Jiang, Xingtai Lv, Kaiyan Zhang, Ning Ding, Youbang Sun, Biqing
  Qi, Yuchen Fan, Xue Kai Zhu, Bowen Zhou
conference: No Venue
year: 2024
bibkey: hua2024fourier
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.17739'}]
tags: ["Model Architecture"]
short_authors: Hua et al.
---
Extending the context length of Language Models (LMs) by improving Rotary Position Embedding (RoPE) has become a trend. While existing works mainly address RoPE's limitations within attention mechanism, this paper provides an analysis across nearly all parts of LMs, uncovering their adverse effects on length generalization for RoPE-based attention. Using Discrete Signal Processing theory, we show that RoPE enables periodic attention by implicitly achieving Non-Uniform Discrete Fourier Transform. However, this periodicity is undermined by the spectral damage caused by: 1) linear layers and activation functions outside of attention; 2) insufficiently trained frequency components brought by time-domain truncation. Building on our observations, we propose Fourier Position Embedding (FoPE), which enhances attention's frequency-domain properties to improve both its periodic extension and length generalization. FoPE constructs Fourier Series and zero-outs the destructive frequency components, increasing model robustness against the spectrum damage. Experiments across various model scales show that, within varying context windows, FoPE can maintain a more stable perplexity and a more consistent accuracy in a needle-in-haystack task compared to RoPE and ALiBi. Several analyses and ablations bring further support to our method and theoretical modeling.

https://huggingface.co/discussions/paper/676a6845bee647b8c004f51c