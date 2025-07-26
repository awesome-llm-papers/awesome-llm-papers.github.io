---
layout: publication
title: 'Beyond A*: Better Planning With Transformers Via Search Dynamics Bootstrapping'
authors: Lucas Lehnert, Sainbayar Sukhbaatar, Paul Mcvay, Michael Rabbat, Yuandong
  Tian
conference: No Venue
year: 2024
bibkey: lehnert2024beyond
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65d8203dbc9081f6c9027f5a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.14083'}]
tags: ["Model Architecture"]
short_authors: Lehnert et al.
---
While Transformers have enabled tremendous progress in various application settings, such architectures still lag behind traditional symbolic planners for solving complex decision making tasks. In this work, we demonstrate how to train Transformers to solve complex planning tasks and present Searchformer, a Transformer model that optimally solves previously unseen Sokoban puzzles 93.7% of the time, while using up to 26.8% fewer search steps than standard A^* search. Searchformer is an encoder-decoder Transformer model trained to predict the search dynamics of A^*. This model is then fine-tuned via expert iterations to perform fewer search steps than A^* search while still generating an optimal plan. In our training method, A^*'s search dynamics are expressed as a token sequence outlining when task states are added and removed into the search tree during symbolic planning. In our ablation studies on maze navigation, we find that Searchformer significantly outperforms baselines that predict the optimal plan directly with a 5-10times smaller model size and a 10times smaller training dataset. We also demonstrate how Searchformer scales to larger and more complex decision making tasks like Sokoban with improved percentage of solved tasks and shortened search dynamics.

https://huggingface.co/discussions/paper/65d8203dbc9081f6c9027f5a