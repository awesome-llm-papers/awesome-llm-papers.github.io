---
layout: publication
title: Grandmaster-level Chess Without Search
authors: "Anian Ruoss, Gr\xE9goire Del\xE9tang, Sourabh Medapati, Jordi Grau-moya,\
  \ Li Kevin Wenliang, Elliot Catt, John Reid, Tim Genewein"
conference: No Venue
year: 2024
bibkey: ruoss2024grandmaster
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.04494'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Ruoss et al.
---
The recent breakthrough successes in machine learning are mainly attributed to scale: namely large-scale attention-based architectures and datasets of unprecedented scale. This paper investigates the impact of training at scale for chess. Unlike traditional chess engines that rely on complex heuristics, explicit search, or a combination of both, we train a 270M parameter transformer model with supervised learning on a dataset of 10 million chess games. We annotate each board in the dataset with action-values provided by the powerful Stockfish 16 engine, leading to roughly 15 billion data points. Our largest model reaches a Lichess blitz Elo of 2895 against humans, and successfully solves a series of challenging chess puzzles, without any domain-specific tweaks or explicit search algorithms. We also show that our model outperforms AlphaZero's policy and value networks (without MCTS) and GPT-3.5-turbo-instruct. A systematic investigation of model and dataset size shows that strong chess performance only arises at sufficient scale. To validate our results, we perform an extensive series of ablations of design choices and hyperparameters.

https://huggingface.co/discussions/paper/65c4687cc3e219990818da66