---
layout: publication
title: 'Falcon Mamba: The First Competitive Attention-free 7B Language Model'
authors: Jingwei Zuo, Maksim Velikanov, Dhia Eddine Rhaiem, Ilyas Chahed, Younes Belkada,
  Guillaume Kunsch, Hakim Hacid
conference: No Venue
year: 2024
bibkey: zuo2024falcon
additional_links: [{name: Code, url: 'https://huggingface.co/tiiuae/falcon-mamba-7b,'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/670761a0d24201cd8c5d384a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.05355'}]
tags: ["Model Architecture"]
short_authors: Zuo et al.
---
In this technical report, we present Falcon Mamba 7B, a new base large language model based on the novel Mamba architecture. Falcon Mamba 7B is trained on 5.8 trillion tokens with carefully selected data mixtures. As a pure Mamba-based model, Falcon Mamba 7B surpasses leading open-weight models based on Transformers, such as Mistral 7B, Llama3.1 8B, and Falcon2 11B. It is on par with Gemma 7B and outperforms models with different architecture designs, such as RecurrentGemma 9B and RWKV-v6 Finch 7B/14B. Currently, Falcon Mamba 7B is the best-performing Mamba model in the literature at this scale, surpassing both existing Mamba and hybrid Mamba-Transformer models, according to the Open LLM Leaderboard. Due to its architecture, Falcon Mamba 7B is significantly faster at inference and requires substantially less memory for long sequence generation. Despite recent studies suggesting that hybrid Mamba-Transformer models outperform pure architecture designs, we demonstrate that even the pure Mamba design can achieve similar, or even superior results compared to the Transformer and hybrid designs. We make the weights of our implementation of Falcon Mamba 7B publicly available on https://huggingface.co/tiiuae/falcon-mamba-7b, under a permissive license.

https://huggingface.co/discussions/paper/670761a0d24201cd8c5d384a