---
layout: publication
title: 'Animegamer: Infinite Anime Life Simulation With Next Game State Prediction'
authors: Junhao Cheng, Yuying Ge, Yixiao Ge, Jing Liao, Ying Shan
conference: No Venue
year: 2025
bibkey: cheng2025animegamer
additional_links: [{name: Code, url: 'https://github.com/TencentARC/AnimeGamer'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67eca39ce14049f5ff06535b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.01014'}]
tags: ["Has Code"]
short_authors: Cheng et al.
---
Recent advancements in image and video synthesis have opened up new promise in generative games. One particularly intriguing application is transforming characters from anime films into interactive, playable entities. This allows players to immerse themselves in the dynamic anime world as their favorite characters for life simulation through language instructions. Such games are defined as infinite game since they eliminate predetermined boundaries and fixed gameplay rules, where players can interact with the game world through open-ended language and experience ever-evolving storylines and environments. Recently, a pioneering approach for infinite anime life simulation employs large language models (LLMs) to translate multi-turn text dialogues into language instructions for image generation. However, it neglects historical visual context, leading to inconsistent gameplay. Furthermore, it only generates static images, failing to incorporate the dynamics necessary for an engaging gaming experience. In this work, we propose AnimeGamer, which is built upon Multimodal Large Language Models (MLLMs) to generate each game state, including dynamic animation shots that depict character movements and updates to character states, as illustrated in Figure 1. We introduce novel action-aware multimodal representations to represent animation shots, which can be decoded into high-quality video clips using a video diffusion model. By taking historical animation shot representations as context and predicting subsequent representations, AnimeGamer can generate games with contextual consistency and satisfactory dynamics. Extensive evaluations using both automated metrics and human evaluations demonstrate that AnimeGamer outperforms existing methods in various aspects of the gaming experience. Codes and checkpoints are available at https://github.com/TencentARC/AnimeGamer.

https://huggingface.co/discussions/paper/67eca39ce14049f5ff06535b