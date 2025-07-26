---
layout: publication
title: 'Tina: Tiny Reasoning Models Via Lora'
authors: "Shangshang Wang, Julian Asilis, \xD6mer Faruk Akg\xFCl, Enes Burak Bilgin,\
  \ Ollie Liu, Willie Neiswanger"
conference: No Venue
year: 2025
bibkey: wang2025tina
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6808452f16c1c427ac7278b1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.15777'}]
tags: ["Efficiency", "Fine-Tuning", "Training Techniques"]
short_authors: Wang et al.
---
How cost-effectively can strong reasoning abilities be achieved in language models? Driven by this fundamental question, we present Tina, a family of tiny reasoning models achieved with high cost-efficiency. Notably, Tina demonstrates that substantial reasoning performance can be developed using only minimal resources, by applying parameter-efficient updates during reinforcement learning (RL), using low-rank adaptation (LoRA), to an already tiny 1.5B parameter base model. This minimalist approach produces models that achieve reasoning performance which is competitive with, and sometimes surpasses, SOTA RL reasoning models built upon the same base model. Crucially, this is achieved at a tiny fraction of the computational post-training cost employed by existing SOTA models. In fact, the best Tina model achieves a >20% reasoning performance increase and 43.33% Pass@1 accuracy on AIME24, at only \$9 USD post-training and evaluation cost (i.e., an estimated 260x cost reduction). Our work reveals the surprising effectiveness of efficient RL reasoning via LoRA. We validate this across multiple open-source reasoning datasets and various ablation settings starting with a single, fixed set of hyperparameters. Furthermore, we hypothesize that this effectiveness and efficiency stem from LoRA rapidly adapting the model to the structural format of reasoning rewarded by RL, while largely preserving the base model's underlying knowledge. In service of accessibility and open research, we fully open-source all code, training logs, and model weights \& checkpoints.

https://huggingface.co/discussions/paper/6808452f16c1c427ac7278b1