---
layout: publication
title: 'Slicegpt: Compress Large Language Models By Deleting Rows And Columns'
authors: Saleh Ashkboos, Maximilian L. Croci, Marcelo Gennari Do Nascimento, Torsten
  Hoefler, James Hensman
conference: No Venue
year: 2024
bibkey: ashkboos2024slicegpt
additional_links: [{name: Code, url: 'https://github.com/microsoft/TransformerCompression'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/65b70e8d4839ccc503a60528'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2401.15024'}]
tags: ["Efficiency", "Has Code", "Model Architecture", "Training Techniques"]
short_authors: Ashkboos et al.
---
Large language models have become the cornerstone of natural language processing, but their use comes with substantial costs in terms of compute and memory resources. Sparsification provides a solution to alleviate these resource constraints, and recent works have shown that trained models can be sparsified post-hoc. Existing sparsification techniques face challenges as they need additional data structures and offer constrained speedup with current hardware. In this paper we present SliceGPT, a new post-training sparsification scheme which replaces each weight matrix with a smaller (dense) matrix, reducing the embedding dimension of the network. Through extensive experimentation, we show that SliceGPT can remove up to 25% of the model parameters (including embeddings) for LLAMA2-70B, OPT 66B and Phi-2 models while maintaining 99%, 99% and 90% zero-shot task performance of the dense model respectively. Our sliced models run on fewer GPUs and run faster without any additional code optimization: on 24GB consumer GPUs we reduce the total compute for inference on LLAMA2-70B to 64% of that of the dense model; on 40GB A100 GPUs we reduce it to 66%. We offer a new insight, computational invariance in transformer networks, which enables SliceGPT and we hope it will inspire and enable future avenues to reduce memory and computation demands for pre-trained models. Code is available at: https://github.com/microsoft/TransformerCompression

https://huggingface.co/discussions/paper/65b70e8d4839ccc503a60528