---
layout: publication
title: Mistral 7B
authors: [albert Q. Jiang, alexandre Sablayrolles, arthur Mensch, chris Bamford, devendra
    Singh Chaplot, diego de Las Casas, florian Bressand, gianna Lengyel, guillaume
    Lample, lucile Saulnier, "l\xE9lio Renard Lavaud", marie-anne Lachaux, pierre
    Stock, teven Le Scao, thibaut Lavril, thomas Wang, "timoth\xE9e Lacroix", william
    El Sayed]
conference: Arxiv
year: 2023
bibkey: albert2023mistral
citations: 149
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2310.06825v1'}]
tags: ["Efficiency", "Instruction Following", "Llm For Code", "Memory & Context"]
short_authors: Jiang et al.
---
We introduce Mistral 7B v0.1, a 7-billion-parameter language model engineered
for superior performance and efficiency. Mistral 7B outperforms Llama 2 13B
across all evaluated benchmarks, and Llama 1 34B in reasoning, mathematics, and
code generation. Our model leverages grouped-query attention (GQA) for faster
inference, coupled with sliding window attention (SWA) to effectively handle
sequences of arbitrary length with a reduced inference cost. We also provide a
model fine-tuned to follow instructions, Mistral 7B -- Instruct, that surpasses
the Llama 2 13B -- Chat model both on human and automated benchmarks. Our
models are released under the Apache 2.0 license.