---
layout: publication
title: 'Smarter, Better, Faster, Longer: A Modern Bidirectional Encoder For Fast,
  Memory Efficient, And Long Context Finetuning And Inference'
authors: "Benjamin Warner, Antoine Chaffin, Benjamin Clavi\xE9, Orion Weller, Oskar\
  \ Hallstr\xF6m, Said Taghadouini, Alexis Gallagher, Raja Biswas, Faisal Ladhak,\
  \ Tom Aarsen, Nathan Cooper, Griffin Adams, Jeremy Howard, Iacopo Poli"
conference: No Venue
year: 2024
bibkey: warner2024smarter
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67638c8ed63e4b348e8a50ae'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.13663'}]
tags: ["Model Architecture"]
short_authors: Warner et al.
---
Encoder-only transformer models such as BERT offer a great performance-size tradeoff for retrieval and classification tasks with respect to larger decoder-only models. Despite being the workhorse of numerous production pipelines, there have been limited Pareto improvements to BERT since its release. In this paper, we introduce ModernBERT, bringing modern model optimizations to encoder-only models and representing a major Pareto improvement over older encoders. Trained on 2 trillion tokens with a native 8192 sequence length, ModernBERT models exhibit state-of-the-art results on a large pool of evaluations encompassing diverse classification tasks and both single and multi-vector retrieval on different domains (including code). In addition to strong downstream performance, ModernBERT is also the most speed and memory efficient encoder and is designed for inference on common GPUs.

https://huggingface.co/discussions/paper/67638c8ed63e4b348e8a50ae