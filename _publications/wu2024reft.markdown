---
layout: publication
title: 'Reft: Representation Finetuning For Language Models'
authors: Zhengxuan Wu, Aryaman Arora, Zheng Wang, Atticus Geiger, Dan Jurafsky, Christopher
  D. Manning, Christopher Potts
conference: No Venue
year: 2024
bibkey: wu2024reft
additional_links: [{name: Code, url: 'https://github.com/stanfordnlp/pyreft'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/660f65b29ff4d088f566346c'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2404.03592'}]
tags: ["Fine-Tuning"]
short_authors: Wu et al.
---
Parameter-efficient fine-tuning (PEFT) methods seek to adapt large models via updates to a small number of weights. However, much prior interpretability work has shown that representations encode rich semantic information, suggesting that editing representations might be a more powerful alternative. Here, we pursue this hypothesis by developing a family of Representation Finetuning (ReFT) methods. ReFT methods operate on a frozen base model and learn task-specific interventions on hidden representations. We define a strong instance of the ReFT family, Low-rank Linear Subspace ReFT (LoReFT). LoReFT is a drop-in replacement for existing PEFTs and learns interventions that are 10x-50x more parameter-efficient than prior state-of-the-art PEFTs. We showcase LoReFT on eight commonsense reasoning tasks, four arithmetic reasoning tasks, Alpaca-Eval v1.0, and GLUE. In all these evaluations, LoReFT delivers the best balance of efficiency and performance, and almost always outperforms state-of-the-art PEFTs. We release a generic ReFT training library publicly at https://github.com/stanfordnlp/pyreft.

https://huggingface.co/discussions/paper/660f65b29ff4d088f566346c