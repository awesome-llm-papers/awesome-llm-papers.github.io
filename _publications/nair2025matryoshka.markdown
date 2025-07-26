---
layout: publication
title: Matryoshka Quantization
authors: Pranav Nair, Puranjay Datta, Jeff Dean, Prateek Jain, Aditya Kusupati
conference: No Venue
year: 2025
bibkey: nair2025matryoshka
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.06786'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Nair et al.
---
Quantizing model weights is critical for reducing the communication and inference costs of large models. However, quantizing models -- especially to low precisions like int4 or int2 -- requires a trade-off in model quality; int2, in particular, is known to severely degrade model quality. Consequently, practitioners are often forced to maintain multiple models with different quantization levels or serve a single model that best satisfies the quality-latency trade-off. On the other hand, integer data types, such as int8, inherently possess a nested (Matryoshka) structure where smaller bit-width integers, like int4 or int2, are nested within the most significant bits. This paper proposes Matryoshka Quantization (MatQuant), a novel multi-scale quantization technique that addresses the challenge of needing multiple quantized models. It allows training and maintaining just one model, which can then be served at different precision levels. Furthermore, due to the co-training and co-distillation regularization provided by MatQuant, the int2 precision models extracted by MatQuant can be up to 10% more accurate than standard int2 quantization (using techniques like QAT or OmniQuant). This represents significant progress in model quantization, demonstrated by the fact that, with the same recipe, an int2 FFN-quantized Gemma-2 9B model is more accurate than an int8 FFN-quantized Gemma-2 2B model.

https://huggingface.co/discussions/paper/67aae91d83b1182df7c0cff6