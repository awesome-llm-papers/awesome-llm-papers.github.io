---
layout: publication
title: 'Clinical Modernbert: An Efficient And Long Context Encoder For Biomedical
  Text'
authors: Lee Simon A., Wu Anthony, Chiang Jeffrey N.
conference: Proceedings of the 20th Workshop on Biomedical Language Processing
year: 2025
bibkey: lee2025clinical
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.03964'}]
tags: [Attention Mechanism, Evaluation, Transformer, BERT, Model Architecture, Datasets]
---
We introduce Clinical ModernBERT, a transformer based encoder pretrained on
large scale biomedical literature, clinical notes, and medical ontologies,
incorporating PubMed abstracts, MIMIC IV clinical data, and medical codes with
their textual descriptions. Building on ModernBERT the current state of the art
natural language text encoder featuring architectural upgrades such as rotary
positional embeddings (RoPE), Flash Attention, and extended context length up
to 8,192 tokens our model adapts these innovations specifically for biomedical
and clinical domains. Clinical ModernBERT excels at producing semantically rich
representations tailored for long context tasks. We validate this both by
analyzing its pretrained weights and through empirical evaluation on a
comprehensive suite of clinical NLP benchmarks.