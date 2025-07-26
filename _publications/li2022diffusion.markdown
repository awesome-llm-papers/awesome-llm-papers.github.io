---
layout: publication
title: Diffusion-lm Improves Controllable Text Generation
authors: Xiang Lisa Li, John Thickstun, Ishaan Gulrajani, Percy Liang, Tatsunori B.
  Hashimoto
conference: Arxiv
year: 2022
bibkey: li2022diffusion
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.14217'}]
tags: ["Training Techniques"]
short_authors: Li et al.
---
Controlling the behavior of language models (LMs) without re-training is a
major open problem in natural language generation. While recent works have
demonstrated successes on controlling simple sentence attributes (e.g.,
sentiment), there has been little progress on complex, fine-grained controls
(e.g., syntactic structure). To address this challenge, we develop a new
non-autoregressive language model based on continuous diffusions that we call
Diffusion-LM. Building upon the recent successes of diffusion models in
continuous domains, Diffusion-LM iteratively denoises a sequence of Gaussian
vectors into word vectors, yielding a sequence of intermediate latent
variables. The continuous, hierarchical nature of these intermediate variables
enables a simple gradient-based algorithm to perform complex, controllable
generation tasks. We demonstrate successful control of Diffusion-LM for six
challenging fine-grained control tasks, significantly outperforming prior work.