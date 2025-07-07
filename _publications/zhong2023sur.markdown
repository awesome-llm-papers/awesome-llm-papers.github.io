---
layout: publication
title: 'Sur-adapter: Enhancing Text-to-image Pre-trained Diffusion Models With Large
  Language Models'
authors: Shanshan Zhong, Zhongzhan Huang, Wushao Wen, Jinghui Qin, Liang Lin
conference: Arxiv
year: 2023
citations: 25
bibkey: zhong2023sur
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.05189'}, {name: Code,
    url: 'https://github.com/Qrange-group/SUR-adapter'}]
tags: [Distillation, Training Techniques, Merging, Fine-Tuning, Efficiency and Optimization,
  Has Code, Prompting]
---
Diffusion models, which have emerged to become popular text-to-image
generation models, can produce high-quality and content-rich images guided by
textual prompts. However, there are limitations to semantic understanding and
commonsense reasoning in existing models when the input prompts are concise
narrative, resulting in low-quality image generation. To improve the capacities
for narrative prompts, we propose a simple-yet-effective parameter-efficient
fine-tuning approach called the Semantic Understanding and Reasoning adapter
(SUR-adapter) for pre-trained diffusion models. To reach this goal, we first
collect and annotate a new dataset SURD which consists of more than 57,000
semantically corrected multi-modal samples. Each sample contains a simple
narrative prompt, a complex keyword-based prompt, and a high-quality image.
Then, we align the semantic representation of narrative prompts to the complex
prompts and transfer knowledge of large language models (LLMs) to our
SUR-adapter via knowledge distillation so that it can acquire the powerful
semantic understanding and reasoning capabilities to build a high-quality
textual semantic representation for text-to-image generation. We conduct
experiments by integrating multiple LLMs and popular pre-trained diffusion
models to show the effectiveness of our approach in enabling diffusion models
to understand and reason concise natural language without image quality
degradation. Our approach can make text-to-image diffusion models easier to use
with better user experience, which demonstrates our approach has the potential
for further advancing the development of user-friendly text-to-image generation
models by bridging the semantic gap between simple narrative prompts and
complex keyword-based prompts. The code is released at
https://github.com/Qrange-group/SUR-adapter.