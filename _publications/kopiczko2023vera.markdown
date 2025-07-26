---
layout: publication
title: 'Vera: Vector-based Random Matrix Adaptation'
authors: Dawid Jan Kopiczko, Tijmen Blankevoort, Yuki Markus Asano
conference: No Venue
year: 2023
bibkey: kopiczko2023vera
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2310.11454'}]
tags: ["Fine-Tuning"]
short_authors: Dawid Jan Kopiczko, Tijmen Blankevoort, Yuki Markus Asano
---
Low-rank adapation (LoRA) is a popular method that reduces the number of trainable parameters when finetuning large language models, but still faces acute storage challenges when scaling to even larger models or deploying numerous per-user or per-task adapted models. In this work, we present Vector-based Random Matrix Adaptation (VeRA), which reduces the number of trainable parameters by 10x compared to LoRA, yet maintains the same performance. It achieves this by using a single pair of low-rank matrices shared across all layers and learning small scaling vectors instead. We demonstrate its effectiveness on the GLUE and E2E benchmarks, and show its application in instruction-following with just 1.4M parameters using the Llama2 7B model.

https://huggingface.co/discussions/paper/652f57626605161149457966