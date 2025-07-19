---
layout: publication
title: Enhancing Training Efficiency Using Packing With Flash Attention
authors: Kundu et al.
conference: Current Opinion in Behavioral Sciences
year: 2024
bibkey: kundu2024enhancing
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.09105'}]
tags: [Training Techniques, Attention Mechanism, Transformer, Model Architecture,
  Efficiency And Optimization, Fine Tuning]
---
Padding is often used in tuning LLM models by adding special tokens to
shorter training examples to match the length of the longest sequence in each
batch. While this ensures uniformity for batch processing, it introduces
inefficiencies by including irrelevant padding tokens in the computation and
wastes GPU resources. Hugging Face SFT trainer has always offered the option to
use packing to combine multiple training examples, allowing for maximal
utilization of GPU resources. However, up till now, it did not offer proper
masking of each packed training example. This capability has been added to
Hugging Face Transformers 4.44. We analyse this new feature and show the
benefits across different variations of packing.