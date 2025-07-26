---
layout: publication
title: 'Transfusion: Predict The Next Token And Diffuse Images With One Multi-modal
  Model'
authors: Chunting Zhou, Lili Yu, Arun Babu, Kushal Tirumala, Michihiro Yasunaga, Leonid
  Shamis, Jacob Kahn, Xuezhe Ma, Luke Zettlemoyer, Omer Levy
conference: No Venue
year: 2024
bibkey: zhou2024transfusion
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.11039'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Zhou et al.
---
We introduce Transfusion, a recipe for training a multi-modal model over discrete and continuous data. Transfusion combines the language modeling loss function (next token prediction) with diffusion to train a single transformer over mixed-modality sequences. We pretrain multiple Transfusion models up to 7B parameters from scratch on a mixture of text and image data, establishing scaling laws with respect to a variety of uni- and cross-modal benchmarks. Our experiments show that Transfusion scales significantly better than quantizing images and training a language model over discrete image tokens. By introducing modality-specific encoding and decoding layers, we can further improve the performance of Transfusion models, and even compress each image to just 16 patches. We further demonstrate that scaling our Transfusion recipe to 7B parameters and 2T multi-modal tokens produces a model that can generate images and text on a par with similar scale diffusion models and language models, reaping the benefits of both worlds.

https://huggingface.co/discussions/paper/66c556197690afd2f4c47e82