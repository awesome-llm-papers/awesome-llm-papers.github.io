---
layout: publication
title: Pre-training Small Base Lms With Fewer Tokens
authors: Sunny Sanyal, Sujay Sanghavi, Alexandros G. Dimakis
conference: No Venue
year: 2024
bibkey: sanyal2024pre
additional_links: [{name: Code, url: 'https://github.com/sanyalsunny111/LLM-Inheritune'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/661c86023557013b631d5ee0'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.08634'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Sunny Sanyal, Sujay Sanghavi, Alexandros G. Dimakis
---
We study the effectiveness of a simple approach to develop a small base language model (LM) starting from an existing large base LM: first inherit a few transformer blocks from the larger LM, and then train this smaller model on a very small subset (0.1%) of the raw pretraining data of the larger model. We call our simple recipe Inheritune and first demonstrate it for building a small base LM with 1.5B parameters using 1B tokens (and a starting few layers of larger LM of 3B parameters); we do this using a single A6000 GPU for less than half a day. Across 9 diverse evaluation datasets as well as the MMLU benchmark, the resulting model compares favorably to publicly available base models of 1B-2B size, some of which have been trained using 50-1000 times more tokens. We investigate Inheritune in a slightly different setting where we train small LMs utilizing larger LMs and their full pre-training dataset. Here we show that smaller LMs trained utilizing some of the layers of GPT2-medium (355M) and GPT-2-large (770M) can effectively match the val loss of their bigger counterparts when trained from scratch for the same number of training steps on OpenWebText dataset with 9B tokens. We analyze our recipe with extensive experiments and demonstrate it efficacy on diverse settings. Our code is available at https://github.com/sanyalsunny111/LLM-Inheritune.

https://huggingface.co/discussions/paper/661c86023557013b631d5ee0