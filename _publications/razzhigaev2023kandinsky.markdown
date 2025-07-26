---
layout: publication
title: 'Kandinsky: An Improved Text-to-image Synthesis With Image Prior And Latent
  Diffusion'
authors: Anton Razzhigaev, Arseniy Shakhmatov, Anastasia Maltseva, Vladimir Arkhipkin,
  Igor Pavlov, Ilya Ryabov, Angelina Kuts, Alexander Panchenko, Andrey Kuznetsov,
  Denis Dimitrov
conference: No Venue
year: 2023
bibkey: razzhigaev2023kandinsky
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/651f645cbe34a5f2cf5da0e4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2310.03502'}]
tags: ["Model Architecture"]
short_authors: Razzhigaev et al.
---
Text-to-image generation is a significant domain in modern computer vision and has achieved substantial improvements through the evolution of generative architectures. Among these, there are diffusion-based models that have demonstrated essential quality enhancements. These models are generally split into two categories: pixel-level and latent-level approaches. We present Kandinsky1, a novel exploration of latent diffusion architecture, combining the principles of the image prior models with latent diffusion techniques. The image prior model is trained separately to map text embeddings to image embeddings of CLIP. Another distinct feature of the proposed model is the modified MoVQ implementation, which serves as the image autoencoder component. Overall, the designed model contains 3.3B parameters. We also deployed a user-friendly demo system that supports diverse generative modes such as text-to-image generation, image fusion, text and image fusion, image variations generation, and text-guided inpainting/outpainting. Additionally, we released the source code and checkpoints for the Kandinsky models. Experimental evaluations demonstrate a FID score of 8.03 on the COCO-30K dataset, marking our model as the top open-source performer in terms of measurable image generation quality.

https://huggingface.co/discussions/paper/651f645cbe34a5f2cf5da0e4