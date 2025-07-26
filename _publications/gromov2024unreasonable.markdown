---
layout: publication
title: The Unreasonable Ineffectiveness Of The Deeper Layers
authors: Andrey Gromov, Kushal Tirumala, Hassan Shapourian, Paolo Glorioso, Daniel
  A. Roberts
conference: No Venue
year: 2024
bibkey: gromov2024unreasonable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.17887'}]
tags: ["Efficiency", "Fine-Tuning", "Security"]
short_authors: Gromov et al.
---
We empirically study a simple layer-pruning strategy for popular families of open-weight pretrained LLMs, finding minimal degradation of performance on different question-answering benchmarks until after a large fraction (up to half) of the layers are removed. To prune these models, we identify the optimal block of layers to prune by considering similarity across layers; then, to "heal" the damage, we perform a small amount of finetuning. In particular, we use parameter-efficient finetuning (PEFT) methods, specifically quantization and Low Rank Adapters (QLoRA), such that each of our experiments can be performed on a single A100 GPU. From a practical perspective, these results suggest that layer pruning methods can complement other PEFT strategies to further reduce computational resources of finetuning on the one hand, and can improve the memory and latency of inference on the other hand. From a scientific perspective, the robustness of these LLMs to the deletion of layers implies either that current pretraining methods are not properly leveraging the parameters in the deeper layers of the network or that the shallow layers play a critical role in storing knowledge.

https://huggingface.co/discussions/paper/66039260759b2e212d08b6dc