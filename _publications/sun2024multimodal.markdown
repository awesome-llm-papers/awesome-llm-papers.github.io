---
layout: publication
title: Multimodal Latent Language Modeling With Next-token Diffusion
authors: Yutao Sun, Hangbo Bao, Wenhui Wang, Zhiliang Peng, Li Dong, Shaohan Huang,
  Jianyong Wang, Furu Wei
conference: No Venue
year: 2024
bibkey: sun2024multimodal
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/675b17ac378af168bbfd6757'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.08635'}]
tags: ["Efficiency", "Security", "Training Techniques"]
short_authors: Sun et al.
---
Multimodal generative models require a unified approach to handle both discrete data (e.g., text and code) and continuous data (e.g., image, audio, video). In this work, we propose Latent Language Modeling (LatentLM), which seamlessly integrates continuous and discrete data using causal Transformers. Specifically, we employ a variational autoencoder (VAE) to represent continuous data as latent vectors and introduce next-token diffusion for autoregressive generation of these vectors. Additionally, we develop sigma-VAE to address the challenges of variance collapse, which is crucial for autoregressive modeling. Extensive experiments demonstrate the effectiveness of LatentLM across various modalities. In image generation, LatentLM surpasses Diffusion Transformers in both performance and scalability. When integrated into multimodal large language models, LatentLM provides a general-purpose interface that unifies multimodal generation and understanding. Experimental results show that LatentLM achieves favorable performance compared to Transfusion and vector quantized models in the setting of scaling up training tokens. In text-to-speech synthesis, LatentLM outperforms the state-of-the-art VALL-E 2 model in speaker similarity and robustness, while requiring 10x fewer decoding steps. The results establish LatentLM as a highly effective and scalable approach to advance large multimodal models.

https://huggingface.co/discussions/paper/675b17ac378af168bbfd6757