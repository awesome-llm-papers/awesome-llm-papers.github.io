---
layout: publication
title: 'LEDITS: Real Image Editing With DDPM Inversion And Semantic Guidance'
authors: "Linoy Tsaban, Apolin\xE1rio Passos"
conference: No Venue
year: 2023
bibkey: tsaban2023ledits
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/64a392bdfbd6fdd06d7dfd21'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2307.00522'}]
tags: ["Model Architecture", "Tools"]
short_authors: "Linoy Tsaban, Apolin\xE1rio Passos"
---
Recent large-scale text-guided diffusion models provide powerful image-generation capabilities. Currently, a significant effort is given to enable the modification of these images using text only as means to offer intuitive and versatile editing. However, editing proves to be difficult for these generative models due to the inherent nature of editing techniques, which involves preserving certain content from the original image. Conversely, in text-based models, even minor modifications to the text prompt frequently result in an entirely distinct result, making attaining one-shot generation that accurately corresponds to the users intent exceedingly challenging. In addition, to edit a real image using these state-of-the-art tools, one must first invert the image into the pre-trained models domain - adding another factor affecting the edit quality, as well as latency. In this exploratory report, we propose LEDITS - a combined lightweight approach for real-image editing, incorporating the Edit Friendly DDPM inversion technique with Semantic Guidance, thus extending Semantic Guidance to real image editing, while harnessing the editing capabilities of DDPM inversion as well. This approach achieves versatile edits, both subtle and extensive as well as alterations in composition and style, while requiring no optimization nor extensions to the architecture.

https://huggingface.co/discussions/paper/64a392bdfbd6fdd06d7dfd21