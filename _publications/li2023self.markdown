---
layout: publication
title: Self-alignment With Instruction Backtranslation
authors: Xian Li, Ping Yu, Chunting Zhou, Timo Schick, Luke Zettlemoyer, Omer Levy,
  Jason Weston, Mike Lewis
conference: No Venue
year: 2023
bibkey: li2023self
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2308.06259'}]
tags: ["Datasets", "Efficiency", "Evaluation", "Instruction Following", "Training Techniques"]
short_authors: Li et al.
---
We present a scalable method to build a high quality instruction following language model by automatically labelling human-written text with corresponding instructions. Our approach, named instruction backtranslation, starts with a language model finetuned on a small amount of seed data, and a given web corpus. The seed model is used to construct training examples by generating instruction prompts for web documents (self-augmentation), and then selecting high quality examples from among these candidates (self-curation). This data is then used to finetune a stronger model. Finetuning LLaMa on two iterations of our approach yields a model that outperforms all other LLaMa-based models on the Alpaca leaderboard not relying on distillation data, demonstrating highly effective self-alignment.

https://huggingface.co/discussions/paper/64d9acf2089bc502cef3611a