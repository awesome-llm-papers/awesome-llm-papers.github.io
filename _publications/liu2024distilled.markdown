---
layout: publication
title: 'Distilled Decoding 1: One-step Sampling Of Image Auto-regressive Models With
  Flow Matching'
authors: Enshu Liu, Xuefei Ning, Yu Wang, Zinan Lin
conference: No Venue
year: 2024
bibkey: liu2024distilled
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.17153'}]
tags: ["Training Techniques"]
short_authors: Liu et al.
---
Autoregressive (AR) models have achieved state-of-the-art performance in text and image generation but suffer from slow generation due to the token-by-token process. We ask an ambitious question: can a pre-trained AR model be adapted to generate outputs in just one or two steps? If successful, this would significantly advance the development and deployment of AR models. We notice that existing works that try to speed up AR generation by generating multiple tokens at once fundamentally cannot capture the output distribution due to the conditional dependencies between tokens, limiting their effectiveness for few-step generation. To address this, we propose Distilled Decoding (DD), which uses flow matching to create a deterministic mapping from Gaussian distribution to the output distribution of the pre-trained AR model. We then train a network to distill this mapping, enabling few-step generation. DD doesn't need the training data of the original AR model, making it more practical.We evaluate DD on state-of-the-art image AR models and present promising results on ImageNet-256. For VAR, which requires 10-step generation, DD enables one-step generation (6.3times speed-up), with an acceptable increase in FID from 4.19 to 9.96. For LlamaGen, DD reduces generation from 256 steps to 1, achieving an 217.8times speed-up with a comparable FID increase from 4.11 to 11.35. In both cases, baseline methods completely fail with FID>100. DD also excels on text-to-image generation, reducing the generation from 256 steps to 2 for LlamaGen with minimal FID increase from 25.70 to 28.95. As the first work to demonstrate the possibility of one-step generation for image AR models, DD challenges the prevailing notion that AR models are inherently slow, and opens up new opportunities for efficient AR generation. The project website is at https://imagination-research.github.io/distilled-decoding.

https://huggingface.co/discussions/paper/676a3072b1618113354d9aa1