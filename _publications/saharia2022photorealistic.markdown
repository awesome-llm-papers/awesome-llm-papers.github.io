---
layout: publication
title: Photorealistic Text-to-image Diffusion Models With Deep Language Understanding
authors: Chitwan Saharia, William Chan, Saurabh Saxena, Lala Li, Jay Whang, Emily
  Denton, Seyed Kamyar Seyed Ghasemipour, Burcu Karagol Ayan, S. Sara Mahdavi, Rapha
  Gontijo Lopes, Tim Salimans, Jonathan Ho, David J Fleet, Mohammad Norouzi
conference: Arxiv
year: 2022
bibkey: saharia2022photorealistic
citations: 1488
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.11487'}]
tags: ["Model Architecture"]
short_authors: Saharia et al.
---
We present Imagen, a text-to-image diffusion model with an unprecedented
degree of photorealism and a deep level of language understanding. Imagen
builds on the power of large transformer language models in understanding text
and hinges on the strength of diffusion models in high-fidelity image
generation. Our key discovery is that generic large language models (e.g. T5),
pretrained on text-only corpora, are surprisingly effective at encoding text
for image synthesis: increasing the size of the language model in Imagen boosts
both sample fidelity and image-text alignment much more than increasing the
size of the image diffusion model. Imagen achieves a new state-of-the-art FID
score of 7.27 on the COCO dataset, without ever training on COCO, and human
raters find Imagen samples to be on par with the COCO data itself in image-text
alignment. To assess text-to-image models in greater depth, we introduce
DrawBench, a comprehensive and challenging benchmark for text-to-image models.
With DrawBench, we compare Imagen with recent methods including VQ-GAN+CLIP,
Latent Diffusion Models, and DALL-E 2, and find that human raters prefer Imagen
over other models in side-by-side comparisons, both in terms of sample quality
and image-text alignment. See https://imagen.research.google/ for an overview
of the results.