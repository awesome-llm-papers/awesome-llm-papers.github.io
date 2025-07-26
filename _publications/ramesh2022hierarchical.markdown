---
layout: publication
title: Hierarchical Text-conditional Image Generation With CLIP Latents
authors: Aditya Ramesh, Prafulla Dhariwal, Alex Nichol, Casey Chu, Mark Chen
conference: Arxiv
year: 2022
bibkey: ramesh2022hierarchical
citations: 1958
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.06125'}]
tags: ["Model Architecture"]
short_authors: Ramesh et al.
---
Contrastive models like CLIP have been shown to learn robust representations
of images that capture both semantics and style. To leverage these
representations for image generation, we propose a two-stage model: a prior
that generates a CLIP image embedding given a text caption, and a decoder that
generates an image conditioned on the image embedding. We show that explicitly
generating image representations improves image diversity with minimal loss in
photorealism and caption similarity. Our decoders conditioned on image
representations can also produce variations of an image that preserve both its
semantics and style, while varying the non-essential details absent from the
image representation. Moreover, the joint embedding space of CLIP enables
language-guided image manipulations in a zero-shot fashion. We use diffusion
models for the decoder and experiment with both autoregressive and diffusion
models for the prior, finding that the latter are computationally more
efficient and produce higher-quality samples.