---
layout: publication
title: One Wide Feedforward Is All You Need
authors: "Telmo Pessoa Pires, Ant\xF3nio V. Lopes, Yannick Assogba, Hendra Setiawan"
conference: No Venue
year: 2023
bibkey: pires2023one
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/64f832741435cc7faa41683d'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2309.01826'}]
tags: ["Model Architecture"]
short_authors: Pires et al.
---
The Transformer architecture has two main non-embedding components: Attention and the Feed Forward Network (FFN). Attention captures interdependencies between words regardless of their position, while the FFN non-linearly transforms each input token independently. In this work we explore the role of the FFN, and find that despite taking up a significant fraction of the model's parameters, it is highly redundant. Concretely, we are able to substantially reduce the number of parameters with only a modest drop in accuracy by removing the FFN on the decoder layers and sharing a single FFN across the encoder. Finally we scale this architecture back to its original size by increasing the hidden dimension of the shared FFN, achieving substantial gains in both accuracy and latency with respect to the original Transformer Big.

https://huggingface.co/discussions/paper/64f832741435cc7faa41683d