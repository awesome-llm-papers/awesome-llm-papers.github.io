---
layout: publication
title: 'Conceptattention: Diffusion Transformers Learn Highly Interpretable Features'
authors: Alec Helbling, Tuna Han Salih Meral, Ben Hoover, Pinar Yanardag, Duen Horng
  Chau
conference: No Venue
year: 2025
bibkey: helbling2025conceptattention
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.04320'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Helbling et al.
---
Do the rich representations of multi-modal diffusion transformers (DiTs) exhibit unique properties that enhance their interpretability? We introduce ConceptAttention, a novel method that leverages the expressive power of DiT attention layers to generate high-quality saliency maps that precisely locate textual concepts within images. Without requiring additional training, ConceptAttention repurposes the parameters of DiT attention layers to produce highly contextualized concept embeddings, contributing the major discovery that performing linear projections in the output space of DiT attention layers yields significantly sharper saliency maps compared to commonly used cross-attention mechanisms. Remarkably, ConceptAttention even achieves state-of-the-art performance on zero-shot image segmentation benchmarks, outperforming 11 other zero-shot interpretability methods on the ImageNet-Segmentation dataset and on a single-class subset of PascalVOC. Our work contributes the first evidence that the representations of multi-modal DiT models like Flux are highly transferable to vision tasks like segmentation, even outperforming multi-modal foundation models like CLIP.

https://huggingface.co/discussions/paper/67a643200fdd5543151da869