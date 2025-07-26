---
layout: publication
title: 'Gemma Scope: Open Sparse Autoencoders Everywhere All At Once On Gemma 2'
authors: "Tom Lieberum, Senthooran Rajamanoharan, Arthur Conmy, Lewis Smith, Nicolas\
  \ Sonnerat, Vikrant Varma, J\xE1nos Kram\xE1r, Anca Dragan, Rohin Shah, Neel Nanda"
conference: No Venue
year: 2024
bibkey: lieberum2024gemma
additional_links: [{name: Code, url: 'https://huggingface.co/google/gemma-scope'},
  {name: Code, url: 'https://www.neuronpedia.org/gemma-scope'}, {name: Code, url: 'https://huggingface.co/discussions/paper/66b97edca0ebe4b8a50f1bd3'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.05147'}]
tags: ["Applications"]
short_authors: Lieberum et al.
---
Sparse autoencoders (SAEs) are an unsupervised method for learning a sparse decomposition of a neural network's latent representations into seemingly interpretable features. Despite recent excitement about their potential, research applications outside of industry are limited by the high cost of training a comprehensive suite of SAEs. In this work, we introduce Gemma Scope, an open suite of JumpReLU SAEs trained on all layers and sub-layers of Gemma 2 2B and 9B and select layers of Gemma 2 27B base models. We primarily train SAEs on the Gemma 2 pre-trained models, but additionally release SAEs trained on instruction-tuned Gemma 2 9B for comparison. We evaluate the quality of each SAE on standard metrics and release these results. We hope that by releasing these SAE weights, we can help make more ambitious safety and interpretability research easier for the community. Weights and a tutorial can be found at https://huggingface.co/google/gemma-scope and an interactive demo can be found at https://www.neuronpedia.org/gemma-scope

https://huggingface.co/discussions/paper/66b97edca0ebe4b8a50f1bd3