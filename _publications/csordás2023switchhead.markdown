---
layout: publication
title: 'Switchhead: Accelerating Transformers With Mixture-of-experts Attention'
authors: "R\xF3bert Csord\xE1s, Piotr Pi\u0119kos, Kazuki Irie, J\xFCrgen Schmidhuber"
conference: No Venue
year: 2023
bibkey: "csord\xE1s2023switchhead"
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/657a68821ccc3c2a5ea66870'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2312.07987'}]
tags: ["Model Architecture"]
short_authors: "Csord\xE1s et al."
---
The costly self-attention layers in modern Transformers require memory and compute quadratic in sequence length. Existing approximation methods usually underperform and fail to obtain significant speedups in practice. Here we present SwitchHead - a novel method that reduces both compute and memory requirements and achieves wall-clock speedup, while matching the language modeling performance of baseline Transformers with the same parameter budget. SwitchHead uses Mixture-of-Experts (MoE) layers for the value and output projections and requires 4 to 8 times fewer attention matrices than standard Transformers. Our novel attention can also be combined with MoE MLP layers, resulting in an efficient fully-MoE "SwitchAll" Transformer model. Our code is public.

https://huggingface.co/discussions/paper/657a68821ccc3c2a5ea66870