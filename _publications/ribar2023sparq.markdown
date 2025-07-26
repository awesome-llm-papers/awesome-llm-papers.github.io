---
layout: publication
title: 'Sparq Attention: Bandwidth-efficient LLM Inference'
authors: Luka Ribar, Ivan Chelombiev, Luke Hudlass-galley, Charlie Blake, Carlo Luschi,
  Douglas Orr
conference: No Venue
year: 2023
bibkey: ribar2023sparq
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2312.04985'}]
tags: ["Applications", "Memory & Context"]
short_authors: Ribar et al.
---
Generative large language models (LLMs) have opened up numerous novel possibilities, but due to their significant computational requirements their ubiquitous use remains challenging. Some of the most useful applications require processing large numbers of samples at a time and using long contexts, both significantly increasing the memory communication load of the models. We introduce SparQ Attention, a technique for increasing the inference throughput of LLMs by reducing the memory bandwidth requirements within the attention blocks through selective fetching of the cached history. Our proposed technique can be applied directly to off-the-shelf LLMs during inference, without requiring any modification to the pre-training setup or additional fine-tuning. We show how SparQ Attention can decrease the attention memory bandwidth requirements up to eight times without any loss in accuracy by evaluating Llama 2 and Pythia models on a wide range of downstream tasks.

https://huggingface.co/discussions/paper/65767c3fe09de6aa746884e9