---
layout: publication
title: 'Mineworld: A Real-time And Open-source Interactive World Model On Minecraft'
authors: Junliang Guo, Yang Ye, Tianyu He, Haoyu Wu, Yushu Jiang, Tim Pearce, Jiang
  Bian
conference: No Venue
year: 2025
bibkey: guo2025mineworld
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67fc7367df5f5d1e87c14ca6'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.08388'}]
tags: ["Evaluation", "Model Architecture"]
short_authors: Guo et al.
---
World modeling is a crucial task for enabling intelligent agents to effectively interact with humans and operate in dynamic environments. In this work, we propose MineWorld, a real-time interactive world model on Minecraft, an open-ended sandbox game which has been utilized as a common testbed for world modeling. MineWorld is driven by a visual-action autoregressive Transformer, which takes paired game scenes and corresponding actions as input, and generates consequent new scenes following the actions. Specifically, by transforming visual game scenes and actions into discrete token ids with an image tokenizer and an action tokenizer correspondingly, we consist the model input with the concatenation of the two kinds of ids interleaved. The model is then trained with next token prediction to learn rich representations of game states as well as the conditions between states and actions simultaneously. In inference, we develop a novel parallel decoding algorithm that predicts the spatial redundant tokens in each frame at the same time, letting models in different scales generate 4 to 7 frames per second and enabling real-time interactions with game players. In evaluation, we propose new metrics to assess not only visual quality but also the action following capacity when generating new scenes, which is crucial for a world model. Our comprehensive evaluation shows the efficacy of MineWorld, outperforming SoTA open-sourced diffusion based world models significantly. The code and model have been released.

https://huggingface.co/discussions/paper/67fc7367df5f5d1e87c14ca6