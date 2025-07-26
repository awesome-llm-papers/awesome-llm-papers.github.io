---
layout: publication
title: Simple And Controllable Music Generation
authors: "Jade Copet, Felix Kreuk, Itai Gat, Tal Remez, David Kant, Gabriel Synnaeve,\
  \ Yossi Adi, Alexandre D\xE9fossez"
conference: No Venue
year: 2023
bibkey: copet2023simple
additional_links: [{name: Code, url: 'https://github.com/facebookresearch/audiocraft'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/64829a5f709d2cdcac4a85b4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2306.05284'}]
tags: ["Has Code"]
short_authors: Copet et al.
---
We tackle the task of conditional music generation. We introduce MusicGen, a single Language Model (LM) that operates over several streams of compressed discrete music representation, i.e., tokens. Unlike prior work, MusicGen is comprised of a single-stage transformer LM together with efficient token interleaving patterns, which eliminates the need for cascading several models, e.g., hierarchically or upsampling. Following this approach, we demonstrate how MusicGen can generate high-quality samples, while being conditioned on textual description or melodic features, allowing better controls over the generated output. We conduct extensive empirical evaluation, considering both automatic and human studies, showing the proposed approach is superior to the evaluated baselines on a standard text-to-music benchmark. Through ablation studies, we shed light over the importance of each of the components comprising MusicGen. Music samples, code, and models are available at https://github.com/facebookresearch/audiocraft.

https://huggingface.co/discussions/paper/64829a5f709d2cdcac4a85b4