---
layout: publication
title: Bootstrapping Language Models With DPO Implicit Rewards
authors: Changyu Chen, Zichen Liu, Chao Du, Tianyu Pang, Qian Liu, Arunesh Sinha,
  Pradeep Varakantham, Min Lin
conference: No Venue
year: 2024
bibkey: chen2024bootstrapping
additional_links: [{name: Code, url: 'https://github.com/sail-sg/dice'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66727d58a8a27a82f40dc4f0'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2406.09760'}]
tags: ["Has Code", "Model Architecture", "Reinforcement Learning", "Training Techniques"]
short_authors: Chen et al.
---
Human alignment in large language models (LLMs) is an active area of research. A recent groundbreaking work, direct preference optimization (DPO), has greatly simplified the process from past work in reinforcement learning from human feedback (RLHF) by bypassing the reward learning stage in RLHF. DPO, after training, provides an implicit reward model. In this work, we make a novel observation that this implicit reward model can by itself be used in a bootstrapping fashion to further align the LLM. Our approach is to use the rewards from a current LLM model to construct a preference dataset, which is then used in subsequent DPO rounds. We incorporate refinements that debias the length of the responses and improve the quality of the preference dataset to further improve our approach. Our approach, named self-alignment with DPO ImpliCit rEwards (DICE), shows great improvements in alignment and achieves superior performance than Gemini Pro on AlpacaEval 2, reaching 27.55% length-controlled win rate against GPT-4 Turbo, but with only 8B parameters and no external feedback. Our code is available at https://github.com/sail-sg/dice.

https://huggingface.co/discussions/paper/66727d58a8a27a82f40dc4f0