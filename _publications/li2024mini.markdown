---
layout: publication
title: 'Mini-gemini: Mining The Potential Of Multi-modality Vision Language Models'
authors: Yanwei Li, Yuechen Zhang, Chengyao Wang, Zhisheng Zhong, Yixin Chen, Ruihang
  Chu, Shaoteng Liu, Jiaya Jia
conference: No Venue
year: 2024
bibkey: li2024mini
additional_links: [{name: Code, url: 'https://github.com/dvlab-research/MiniGemini'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6604d0937e71d1d4b928fadd'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2403.18814'}]
tags: ["Model Architecture"]
short_authors: Li et al.
---
In this work, we introduce Mini-Gemini, a simple and effective framework enhancing multi-modality Vision Language Models (VLMs). Despite the advancements in VLMs facilitating basic visual dialog and reasoning, a performance gap persists compared to advanced models like GPT-4 and Gemini. We try to narrow the gap by mining the potential of VLMs for better performance and any-to-any workflow from three aspects, i.e., high-resolution visual tokens, high-quality data, and VLM-guided generation. To enhance visual tokens, we propose to utilize an additional visual encoder for high-resolution refinement without increasing the visual token count. We further construct a high-quality dataset that promotes precise image comprehension and reasoning-based generation, expanding the operational scope of current VLMs. In general, Mini-Gemini further mines the potential of VLMs and empowers current frameworks with image understanding, reasoning, and generation simultaneously. Mini-Gemini supports a series of dense and MoE Large Language Models (LLMs) from 2B to 34B. It is demonstrated to achieve leading performance in several zero-shot benchmarks and even surpasses the developed private models. Code and models are available at https://github.com/dvlab-research/MiniGemini.

https://huggingface.co/discussions/paper/6604d0937e71d1d4b928fadd