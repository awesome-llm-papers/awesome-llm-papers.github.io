---
layout: publication
title: Wavelets Are All You Need For Autoregressive Image Generation
authors: Wael Mattar, Idan Levy, Nir Sharon, Shai Dekel
conference: No Venue
year: 2024
bibkey: mattar2024wavelets
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.19997'}]
tags: ["Model Architecture"]
short_authors: Mattar et al.
---
In this paper, we take a new approach to autoregressive image generation that is based on two main ingredients. The first is wavelet image coding, which allows to tokenize the visual details of an image from coarse to fine details by ordering the information starting with the most significant bits of the most significant wavelet coefficients. The second is a variant of a language transformer whose architecture is re-designed and optimized for token sequences in this 'wavelet language'. The transformer learns the significant statistical correlations within a token sequence, which are the manifestations of well-known correlations between the wavelet subbands at various resolutions. We show experimental results with conditioning on the generation process.

https://huggingface.co/discussions/paper/6682e226f80f97532edd4a2f