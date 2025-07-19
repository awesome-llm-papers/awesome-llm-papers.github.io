---
layout: publication
title: Vision-llms Can Fool Themselves With Self-generated Typographic Attacks
authors: Qraitem et al.
conference: Nature
year: 2024
bibkey: qraitem2024vision
citations: 234
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.00626'}]
tags: [GPT, Model Architecture, Security, Applications, Multimodal Models]
---
Typographic attacks, adding misleading text to images, can deceive
vision-language models (LVLMs). The susceptibility of recent large LVLMs like
GPT4-V to such attacks is understudied, raising concerns about amplified
misinformation in personal assistant applications. Previous attacks use simple
strategies, such as random misleading words, which don't fully exploit LVLMs'
language reasoning abilities. We introduce an experimental setup for testing
typographic attacks on LVLMs and propose two novel self-generated attacks: (1)
Class-based attacks, where the model identifies a similar class to deceive
itself, and (2) Reasoned attacks, where an advanced LVLM suggests an attack
combining a deceiving class and description. Our experiments show these attacks
significantly reduce classification performance by up to 60% and are effective
across different models, including InstructBLIP and MiniGPT4. Code:
https://github.com/mqraitem/Self-Gen-Typo-Attack