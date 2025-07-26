---
layout: publication
title: 'Riemannlora: A Unified Riemannian Framework For Ambiguity-free Lora Optimization'
authors: Vladimir Bogachev, Vladimir Aletov, Alexander Molozhavenko, Denis Bobkov,
  Vera Soboleva, Aibek Alanov, Maxim Rakhuba
conference: No Venue
year: 2025
bibkey: bogachev2025riemannlora
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.12142'}]
tags: ["Efficiency", "Model Architecture", "Tools"]
short_authors: Bogachev et al.
---
Low-Rank Adaptation (LoRA) has become a widely adopted standard for parameter-efficient fine-tuning of large language models (LLMs), significantly reducing memory and computational demands. However, challenges remain, including finding optimal initialization strategies or mitigating overparametrization in low-rank matrix factorization. In this work, we propose a novel approach that addresses both of the challenges simultaneously within a unified framework. Our method treats a set of fixed-rank LoRA matrices as a smooth manifold. Considering adapters as elements on this manifold removes overparametrization, while determining the direction of the fastest loss decrease along the manifold provides initialization. Special care is taken to obtain numerically stable and computationally efficient implementation of our method, using best practices from numerical linear algebra and Riemannian optimization. Experimental results on LLM and diffusion model architectures demonstrate that RiemannLoRA consistently improves both convergence speed and final performance over standard LoRA and its state-of-the-art modifications.

https://huggingface.co/discussions/paper/687a4aa4ff51f13d38630272