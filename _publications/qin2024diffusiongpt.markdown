---
layout: publication
title: 'Diffusiongpt: Llm-driven Text-to-image Generation System'
authors: Jie Qin, Jie Wu, Weifeng Chen, Yuxi Ren, Huixia Li, Hefeng Wu, Xuefeng Xiao,
  Rui Wang, Shilei Wen
conference: No Venue
year: 2024
bibkey: qin2024diffusiongpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.10061'}]
tags: ["Prompting"]
short_authors: Qin et al.
---
Diffusion models have opened up new avenues for the field of image generation, resulting in the proliferation of high-quality models shared on open-source platforms. However, a major challenge persists in current text-to-image systems are often unable to handle diverse inputs, or are limited to single model results. Current unified attempts often fall into two orthogonal aspects: i) parse Diverse Prompts in input stage; ii) activate expert model to output. To combine the best of both worlds, we propose DiffusionGPT, which leverages Large Language Models (LLM) to offer a unified generation system capable of seamlessly accommodating various types of prompts and integrating domain-expert models. DiffusionGPT constructs domain-specific Trees for various generative models based on prior knowledge. When provided with an input, the LLM parses the prompt and employs the Trees-of-Thought to guide the selection of an appropriate model, thereby relaxing input constraints and ensuring exceptional performance across diverse domains. Moreover, we introduce Advantage Databases, where the Tree-of-Thought is enriched with human feedback, aligning the model selection process with human preferences. Through extensive experiments and comparisons, we demonstrate the effectiveness of DiffusionGPT, showcasing its potential for pushing the boundaries of image synthesis in diverse domains.

https://huggingface.co/discussions/paper/65a9e21fd766c6c6409f3507