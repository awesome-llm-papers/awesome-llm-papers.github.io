---
layout: publication
title: 'Dreamdiffusion: Generating High-quality Images From Brain EEG Signals'
authors: Yunpeng Bai, Xintao Wang, Yanpei Cao, Yixiao Ge, Chun Yuan, Ying Shan
conference: No Venue
year: 2023
bibkey: bai2023dreamdiffusion
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/649e434ad61f393407b239c5'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2306.16934'}]
tags: ["Applications"]
short_authors: Bai et al.
---
This paper introduces DreamDiffusion, a novel method for generating high-quality images directly from brain electroencephalogram (EEG) signals, without the need to translate thoughts into text. DreamDiffusion leverages pre-trained text-to-image models and employs temporal masked signal modeling to pre-train the EEG encoder for effective and robust EEG representations. Additionally, the method further leverages the CLIP image encoder to provide extra supervision to better align EEG, text, and image embeddings with limited EEG-image pairs. Overall, the proposed method overcomes the challenges of using EEG signals for image generation, such as noise, limited information, and individual differences, and achieves promising results. Quantitative and qualitative results demonstrate the effectiveness of the proposed method as a significant step towards portable and low-cost ``thoughts-to-image'', with potential applications in neuroscience and computer vision.

https://huggingface.co/discussions/paper/649e434ad61f393407b239c5