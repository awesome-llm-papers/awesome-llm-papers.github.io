---
layout: publication
title: 'Tokenverse: Versatile Multi-concept Personalization In Token Modulation Space'
authors: Daniel Garibi, Shahar Yadin, Roni Paiss, Omer Tov, Shiran Zada, Ariel Ephrat,
  Tomer Michaeli, Inbar Mosseri, Tali Dekel
conference: No Venue
year: 2025
bibkey: garibi2025tokenverse
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.12224'}]
tags: ["Efficiency", "Has Code", "Tools"]
short_authors: Garibi et al.
---
We present TokenVerse -- a method for multi-concept personalization, leveraging a pre-trained text-to-image diffusion model. Our framework can disentangle complex visual elements and attributes from as little as a single image, while enabling seamless plug-and-play generation of combinations of concepts extracted from multiple images. As opposed to existing works, TokenVerse can handle multiple images with multiple concepts each, and supports a wide-range of concepts, including objects, accessories, materials, pose, and lighting. Our work exploits a DiT-based text-to-image model, in which the input text affects the generation through both attention and modulation (shift and scale). We observe that the modulation space is semantic and enables localized control over complex concepts. Building on this insight, we devise an optimization-based framework that takes as input an image and a text description, and finds for each word a distinct direction in the modulation space. These directions can then be used to generate new images that combine the learned concepts in a desired configuration. We demonstrate the effectiveness of TokenVerse in challenging personalization settings, and showcase its advantages over existing methods. project's webpage in https://token-verse.github.io/

https://huggingface.co/discussions/paper/6790db6c88d8a90790d9a0f7