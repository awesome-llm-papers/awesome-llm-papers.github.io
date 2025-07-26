---
layout: publication
title: You Do Not Fully Utilize Transformer's Representation Capacity
authors: Gleb Gerasimov, Yaroslav Aksenov, Nikita Balagansky, Viacheslav Sinii, Daniil
  Gavrilov
conference: No Venue
year: 2025
bibkey: gerasimov2025you
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.09245'}]
tags: ["Model Architecture"]
short_authors: Gerasimov et al.
---
In contrast to RNNs, which compress previous tokens into a single hidden state, Transformers can attend to all previous tokens directly. However, standard Transformers only use representations from the immediately preceding layer. In this paper, we show that this design choice causes representation collapse and leads to suboptimal performance. To address this issue, we introduce Layer-Integrated Memory (LIMe), a simple yet powerful approach that preserves the model's overall memory footprint while expanding its representational capacity by allowing access to hidden states from earlier layers. Through extensive experiments across various architectures and different lookup mechanisms, we demonstrate consistent performance improvements on a wide range of tasks. Moreover, our analysis of the learned representation dynamics and our exploration of depthwise circuits reveal how LIMe integrates information across layers, pointing to promising directions for future research.

https://huggingface.co/discussions/paper/67b57a9a3d4f319f1fa94274