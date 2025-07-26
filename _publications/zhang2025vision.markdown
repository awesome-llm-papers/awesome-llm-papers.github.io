---
layout: publication
title: 'Vision-language-vision Auto-encoder: Scalable Knowledge Distillation From
  Diffusion Models'
authors: Tiezheng Zhang, Yitong Li, Yu-cheng Chou, Jieneng Chen, Alan Yuille, Chen
  Wei, Junfei Xiao
conference: No Venue
year: 2025
bibkey: zhang2025vision
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/686f95e9706a6ea465418a06'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.07104'}]
tags: ["Model Architecture"]
short_authors: Zhang et al.
---
Building state-of-the-art Vision-Language Models (VLMs) with strong captioning capabilities typically necessitates training on billions of high-quality image-text pairs, requiring millions of GPU hours. This paper introduces the Vision-Language-Vision (VLV) auto-encoder framework, which strategically leverages key pretrained components: a vision encoder, the decoder of a Text-to-Image (T2I) diffusion model, and subsequently, a Large Language Model (LLM). Specifically, we establish an information bottleneck by regularizing the language representation space, achieved through freezing the pretrained T2I diffusion decoder. Our VLV pipeline effectively distills knowledge from the text-conditioned diffusion model using continuous embeddings, demonstrating comprehensive semantic understanding via high-quality reconstructions. Furthermore, by fine-tuning a pretrained LLM to decode the intermediate language representations into detailed descriptions, we construct a state-of-the-art (SoTA) captioner comparable to leading models like GPT-4o and Gemini 2.0 Flash. Our method demonstrates exceptional cost-efficiency and significantly reduces data requirements; by primarily utilizing single-modal images for training and maximizing the utility of existing pretrained models (image encoder, T2I diffusion model, and LLM), it circumvents the need for massive paired image-text datasets, keeping the total training expenditure under $1,000 USD.

https://huggingface.co/discussions/paper/686f95e9706a6ea465418a06