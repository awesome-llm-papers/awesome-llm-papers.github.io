---
layout: publication
title: 'Mambabyte: Token-free Selective State Space Model'
authors: Junxiong Wang, Tushaar Gangavarapu, Jing Nathan Yan, Alexander M Rush
conference: No Venue
year: 2024
bibkey: wang2024mambabyte
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.13660'}]
tags: ["Efficiency"]
short_authors: Wang et al.
---
Token-free language models learn directly from raw bytes and remove the bias of subword tokenization. Operating on bytes, however, results in significantly longer sequences, and standard autoregressive Transformers scale poorly in such settings. We experiment with MambaByte, a token-free adaptation of the Mamba state space model, trained autoregressively on byte sequences. Our experiments indicate the computational efficiency of MambaByte compared to other byte-level models. We also find MambaByte to be competitive with and even outperform state-of-the-art subword Transformers. Furthermore, owing to linear scaling in length, MambaByte benefits from fast inference compared to Transformers. Our findings establish the viability of MambaByte in enabling token-free language modeling.

https://huggingface.co/discussions/paper/65b1c0adf32c79fea71cc3c1