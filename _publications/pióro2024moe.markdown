---
layout: publication
title: 'Moe-mamba: Efficient Selective State Space Models With Mixture Of Experts'
authors: "Maciej Pi\xF3ro, Kamil Ciebiera, Krystian Kr\xF3l, Jan Ludziejewski, Sebastian\
  \ Jaszczur"
conference: No Venue
year: 2024
bibkey: "pi\xF3ro2024moe"
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.04081'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: "Pi\xF3ro et al."
---
State Space Models (SSMs) have become serious contenders in the field of sequential modeling, challenging the dominance of Transformers. At the same time, Mixture of Experts (MoE) has significantly improved Transformer-based LLMs, including recent state-of-the-art open-source models. We propose that to unlock the potential of SSMs for scaling, they should be combined with MoE. We showcase this on Mamba, a recent SSM-based model that achieves remarkable, Transformer-like performance. Our model, MoE-Mamba, outperforms both Mamba and Transformer-MoE. In particular, MoE-Mamba reaches the same performance as Mamba in 2.2x less training steps while preserving the inference performance gains of Mamba against the Transformer.

https://huggingface.co/discussions/paper/659ccb1918ad5521982c606b