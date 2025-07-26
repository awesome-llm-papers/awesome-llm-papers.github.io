---
layout: publication
title: 'Block Diffusion: Interpolating Between Autoregressive And Diffusion Language
  Models'
authors: Marianne Arriola, Aaron Gokaslan, Justin T Chiu, Zhihan Yang, Zhixuan Qi,
  Jiaqi Han, Subham Sekhar Sahoo, Volodymyr Kuleshov
conference: No Venue
year: 2025
bibkey: arriola2025block
additional_links: [{name: Code, url: 'https://m-arriola.com/bd3lms/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67d2511e7d0fc37e67269fbf'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2503.09573'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Arriola et al.
---
Diffusion language models offer unique benefits over autoregressive models due to their potential for parallelized generation and controllability, yet they lag in likelihood modeling and are limited to fixed-length generation. In this work, we introduce a class of block diffusion language models that interpolate between discrete denoising diffusion and autoregressive models. Block diffusion overcomes key limitations of both approaches by supporting flexible-length generation and improving inference efficiency with KV caching and parallel token sampling. We propose a recipe for building effective block diffusion models that includes an efficient training algorithm, estimators of gradient variance, and data-driven noise schedules to minimize the variance. Block diffusion sets a new state-of-the-art performance among diffusion models on language modeling benchmarks and enables generation of arbitrary-length sequences. We provide the code, along with the model weights and blog post on the project page: https://m-arriola.com/bd3lms/

https://huggingface.co/discussions/paper/67d2511e7d0fc37e67269fbf