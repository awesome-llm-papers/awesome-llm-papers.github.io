---
layout: publication
title: Continuous Diffusion Model For Language Modeling
authors: Jaehyeong Jo, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: jo2025continuous
additional_links: [{name: Code, url: 'https://github.com/harryjo97/RDLM\{https://github.com/harryjo97/RDLM\'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67b40f94aba9e111862052d5'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.11564'}]
tags: ["Has Code", "Tools", "Training Techniques"]
short_authors: Jaehyeong Jo, Sung Ju Hwang
---
Diffusion models have emerged as a promising alternative to autoregressive models in modeling discrete categorical data. Yet diffusion models that directly work on discrete data space do not fully exploit the power of iterative refinement, as the signals are lost during the transition between discrete states. Existing continuous diffusion models for discrete data have limited performance compared to discrete approaches, and the unclear link between them restricts the development of diffusion models for discrete data. In this work, we propose a continuous diffusion model for language modeling that incorporates the geometry of the underlying categorical distribution. We establish a connection between the discrete diffusion and continuous flow on the statistical manifold, and building on the analogy, we introduce a simple design for the diffusion process that generalizes previous discrete diffusion models. We further propose a simulation-free training framework based on radial symmetry and a simple technique to address the high dimensionality of the manifold. Comprehensive experiments on language modeling benchmarks and other modalities show that our method outperforms existing discrete diffusion models and approaches the performance of autoregressive models. Codes available at https://github.com/harryjo97/RDLM\{https://github.com/harryjo97/RDLM\}.

https://huggingface.co/discussions/paper/67b40f94aba9e111862052d5