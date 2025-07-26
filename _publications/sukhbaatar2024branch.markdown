---
layout: publication
title: 'Branch-train-mix: Mixing Expert Llms Into A Mixture-of-experts LLM'
authors: "Sainbayar Sukhbaatar, Olga Golovneva, Vasu Sharma, Hu Xu, Xi Victoria Lin,\
  \ Baptiste Rozi\xE8re, Jacob Kahn, Daniel Li, Wen-tau Yih, Jason Weston, Xian Li"
conference: No Venue
year: 2024
bibkey: sukhbaatar2024branch
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.07816'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Sukhbaatar et al.
---
We investigate efficient methods for training Large Language Models (LLMs) to possess capabilities in multiple specialized domains, such as coding, math reasoning and world knowledge. Our method, named Branch-Train-MiX (BTX), starts from a seed model, which is branched to train experts in embarrassingly parallel fashion with high throughput and reduced communication cost. After individual experts are asynchronously trained, BTX brings together their feedforward parameters as experts in Mixture-of-Expert (MoE) layers and averages the remaining parameters, followed by an MoE-finetuning stage to learn token-level routing. BTX generalizes two special cases, the Branch-Train-Merge method, which does not have the MoE finetuning stage to learn routing, and sparse upcycling, which omits the stage of training experts asynchronously. Compared to alternative approaches, BTX achieves the best accuracy-efficiency tradeoff.

https://huggingface.co/discussions/paper/65f114b632c29f9fb7031e38