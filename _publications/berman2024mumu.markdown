---
layout: publication
title: 'MUMU: Bootstrapping Multimodal Image Generation From Text-to-image Data'
authors: William Berman, Alexander Peysakhovich
conference: No Venue
year: 2024
bibkey: berman2024mumu
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/667ec710a7d8b1deba80b273'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.18790'}]
tags: ["Datasets"]
short_authors: William Berman, Alexander Peysakhovich
---
We train a model to generate images from multimodal prompts of interleaved text and images such as "a <picture of a man> man and his <picture of a dog> dog in an <picture of a cartoon> animated style." We bootstrap a multimodal dataset by extracting semantically meaningful image crops corresponding to words in the image captions of synthetically generated and publicly available text-image data. Our model, MUMU, is composed of a vision-language model encoder with a diffusion decoder and is trained on a single 8xH100 GPU node. Despite being only trained on crops from the same image, MUMU learns to compose inputs from different images into a coherent output. For example, an input of a realistic person and a cartoon will output the same person in the cartoon style, and an input of a standing subject and a scooter will output the subject riding the scooter. As a result, our model generalizes to tasks such as style transfer and character consistency. Our results show the promise of using multimodal models as general purpose controllers for image generation.

https://huggingface.co/discussions/paper/667ec710a7d8b1deba80b273