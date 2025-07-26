---
layout: publication
title: 'Block Transformer: Global-to-local Language Modeling For Fast Inference'
authors: Namgyu Ho, Sangmin Bae, Taehyeon Kim, Hyunjik Jo, Yireun Kim, Tal Schuster,
  Adam Fisch, James Thorne, Se-young Yun
conference: No Venue
year: 2024
bibkey: ho2024block
additional_links: [{name: Code, url: 'https://github.com/itsnamgyu/block-transformer'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/666120854e5af73c6a4ea9af'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.02657'}]
tags: ["Memory & Context", "Model Architecture"]
short_authors: Ho et al.
---
This paper presents the Block Transformer architecture which adopts hierarchical global-to-local modeling to autoregressive transformers to mitigate the inference bottlenecks of self-attention. To apply self-attention, the key-value (KV) cache of all previous sequences must be retrieved from memory at every decoding step. Thereby, this KV cache IO becomes a significant bottleneck in batch inference. We notice that these costs stem from applying self-attention on the global context, therefore we isolate the expensive bottlenecks of global modeling to lower layers and apply fast local modeling in upper layers. To mitigate the remaining costs in the lower layers, we aggregate input tokens into fixed size blocks and then apply self-attention at this coarse level. Context information is aggregated into a single embedding to enable upper layers to decode the next block of tokens, without global attention. Free of global attention bottlenecks, the upper layers can fully utilize the compute hardware to maximize inference throughput. By leveraging global and local modules, the Block Transformer architecture demonstrates 10-20x gains in inference throughput compared to vanilla transformers with equivalent perplexity. Our work introduces a new approach to optimize language model inference through novel application of global-to-local modeling. Code is available at https://github.com/itsnamgyu/block-transformer.

https://huggingface.co/discussions/paper/666120854e5af73c6a4ea9af