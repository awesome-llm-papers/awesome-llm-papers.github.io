---
layout: publication
title: 'Griffin: Mixing Gated Linear Recurrences With Local Attention For Efficient
  Language Models'
authors: Soham de, Samuel L. Smith, Anushan Fernando, Aleksandar Botev, George Cristian-muraru,
  Albert Gu, Ruba Haroun, Leonard Berrada, Yutian Chen, Srivatsan Srinivasan, Guillaume
  Desjardins, Arnaud Doucet, David Budden, Yee Whye Teh, Razvan Pascanu, Nando de
  Freitas, Caglar Gulcehre
conference: No Venue
year: 2024
bibkey: de2024griffin
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65e155a99944a44329e45388'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.19427'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: de et al.
---
Recurrent neural networks (RNNs) have fast inference and scale efficiently on long sequences, but they are difficult to train and hard to scale. We propose Hawk, an RNN with gated linear recurrences, and Griffin, a hybrid model that mixes gated linear recurrences with local attention. Hawk exceeds the reported performance of Mamba on downstream tasks, while Griffin matches the performance of Llama-2 despite being trained on over 6 times fewer tokens. We also show that Griffin can extrapolate on sequences significantly longer than those seen during training. Our models match the hardware efficiency of Transformers during training, and during inference they have lower latency and significantly higher throughput. We scale Griffin up to 14B parameters, and explain how to shard our models for efficient distributed training.

https://huggingface.co/discussions/paper/65e155a99944a44329e45388