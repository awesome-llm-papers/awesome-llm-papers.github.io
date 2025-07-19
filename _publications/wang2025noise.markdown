---
layout: publication
title: 'Noise-robustness Through Noise: Asymmetric Lora Adaption With Poisoning Expert'
authors: Wang et al.
conference: Proceedings of the 56th Annual Design Automation Conference 2019
year: 2025
bibkey: wang2025noise
citations: 117
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.23868'}]
tags: [RAG, Training Techniques, Tools, Model Architecture, Security, Fine Tuning]
---
Current parameter-efficient fine-tuning methods for adapting pre-trained language models to downstream tasks are susceptible to interference from noisy data. Conventional noise-handling approaches either rely on laborious data pre-processing or employ model architecture modifications prone to error accumulation. In contrast to existing noise-process paradigms, we propose a noise-robust adaptation method via asymmetric LoRA poisoning experts (LoPE), a novel framework that enhances model robustness to noise only with generated noisy data. Drawing inspiration from the mixture-of-experts architecture, LoPE strategically integrates a dedicated poisoning expert in an asymmetric LoRA configuration. Through a two-stage paradigm, LoPE performs noise injection on the poisoning expert during fine-tuning to enhance its noise discrimination and processing ability. During inference, we selectively mask the dedicated poisoning expert to leverage purified knowledge acquired by normal experts for noise-robust output. Extensive experiments demonstrate that LoPE achieves strong performance and robustness purely through the low-cost noise injection, which completely eliminates the requirement of data cleaning.