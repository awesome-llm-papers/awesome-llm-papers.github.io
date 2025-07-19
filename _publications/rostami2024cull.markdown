---
layout: publication
title: 'CULL-MT: Compression Using Language And Layer Pruning For Machine Translation'
authors: Rostami Pedram, Dousti Mohammad Javad
conference: Proceedings of The 20th SIGNLL Conference on Computational Natural Language
  Learning
year: 2024
bibkey: rostami2024cull
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.06506'}]
tags: [RAG, Training Techniques, Distillation, Efficiency And Optimization, Reinforcement
    Learning, Applications, Fine Tuning, Pruning]
---
Multilingual machine translation models often outperform traditional
bilingual models by leveraging translation knowledge transfer. Recent
advancements have led to these models supporting hundreds of languages and
achieving state-of-the-art results across various translation directions.
However, as these models grow larger, their inference operations become
increasingly costly. In many use cases, there is no need to support such a wide
range of language pairs, as translation is typically needed in only a few
selected directions. In this paper, we present CULL-MT, a compression method
for machine translation models based on structural layer pruning and selected
language directions. Our approach identifies and prunes unimportant layers
using a greedy strategy, then mitigates the impact by applying knowledge
distillation from the original model along with parameter-efficient
fine-tuning. We apply CULL-MT to the NLLB-3.3B and LLaMA3.1-8B-Instruct models.
In a multi-way translation scenario (Persian, French, and German to English),
we find the NLLB-3.3B model to be robust, allowing 25% of layers to be pruned
with only a 0.9 spBLEU drop. However, LLaMA3.1-8B-Instruct is more sensitive,
with a 2.0 spBLEU drop after pruning 5 layers.