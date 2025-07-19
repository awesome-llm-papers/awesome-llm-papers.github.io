---
layout: publication
title: 'LLM4DSR: Leveraging Large Language Model For Denoising Sequential Recommendation'
authors: Wang et al.
conference: Proceedings of the 17th ACM Conference on Recommender Systems
year: 2024
bibkey: wang2024llm4dsr
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.08208'}]
tags: [Fine Tuning, Training Techniques, RAG, RecSys, Reinforcement Learning]
---
Sequential Recommenders generate recommendations based on users' historical interaction sequences. However, in practice, these collected sequences are often contaminated by noisy interactions, which significantly impairs recommendation performance. Accurately identifying such noisy interactions without additional information is particularly challenging due to the absence of explicit supervisory signals indicating noise. Large Language Models (LLMs), equipped with extensive open knowledge and semantic reasoning abilities, offer a promising avenue to bridge this information gap. However, employing LLMs for denoising in sequential recommendation presents notable challenges: 1) Direct application of pretrained LLMs may not be competent for the denoising task, frequently generating nonsensical responses; 2) Even after fine-tuning, the reliability of LLM outputs remains questionable, especially given the complexity of the denoising task and the inherent hallucinatory issue of LLMs.
  To tackle these challenges, we propose LLM4DSR, a tailored approach for denoising sequential recommendation using LLMs. We constructed a self-supervised fine-tuning task to activate LLMs' capabilities to identify noisy items and suggest replacements. Furthermore, we developed an uncertainty estimation module that ensures only high-confidence responses are utilized for sequence corrections. Remarkably, LLM4DSR is model-agnostic, allowing corrected sequences to be flexibly applied across various recommendation models. Extensive experiments validate the superiority of LLM4DSR over existing methods.