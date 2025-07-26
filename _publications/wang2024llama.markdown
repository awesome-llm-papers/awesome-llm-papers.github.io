---
layout: publication
title: 'Llama-mesh: Unifying 3D Mesh Generation With Language Models'
authors: Zhengyi Wang, Jonathan Lorraine, Yikai Wang, Hang Su, Jun Zhu, Sanja Fidler,
  Xiaohui Zeng
conference: No Venue
year: 2024
bibkey: wang2024llama
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.09595'}]
tags: ["Datasets", "Fine-Tuning"]
short_authors: Wang et al.
---
This work explores expanding the capabilities of large language models (LLMs) pretrained on text to generate 3D meshes within a unified model. This offers key advantages of (1) leveraging spatial knowledge already embedded in LLMs, derived from textual sources like 3D tutorials, and (2) enabling conversational 3D generation and mesh understanding. A primary challenge is effectively tokenizing 3D mesh data into discrete tokens that LLMs can process seamlessly. To address this, we introduce LLaMA-Mesh, a novel approach that represents the vertex coordinates and face definitions of 3D meshes as plain text, allowing direct integration with LLMs without expanding the vocabulary. We construct a supervised fine-tuning (SFT) dataset enabling pretrained LLMs to (1) generate 3D meshes from text prompts, (2) produce interleaved text and 3D mesh outputs as required, and (3) understand and interpret 3D meshes. Our work is the first to demonstrate that LLMs can be fine-tuned to acquire complex spatial knowledge for 3D mesh generation in a text-based format, effectively unifying the 3D and text modalities. LLaMA-Mesh achieves mesh generation quality on par with models trained from scratch while maintaining strong text generation performance.

https://huggingface.co/discussions/paper/6736d0f967d01d58999f716d