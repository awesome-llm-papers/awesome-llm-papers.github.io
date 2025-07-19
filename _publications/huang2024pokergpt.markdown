---
layout: publication
title: 'Pokergpt: An End-to-end Lightweight Solver For Multi-player Texas Hold''em
  Via Large Language Model'
authors: Huang et al.
conference: IEEE Robotics and Automation Letters
year: 2024
bibkey: huang2024pokergpt
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.06781'}]
tags: [Training Techniques, GPT, Prompting, Agentic, Model Architecture, Reinforcement
    Learning, Applications, Fine Tuning]
---
Poker, also known as Texas Hold'em, has always been a typical research target
within imperfect information games (IIGs). IIGs have long served as a measure
of artificial intelligence (AI) development. Representative prior works, such
as DeepStack and Libratus heavily rely on counterfactual regret minimization
(CFR) to tackle heads-up no-limit Poker. However, it is challenging for
subsequent researchers to learn CFR from previous models and apply it to other
real-world applications due to the expensive computational cost of CFR
iterations. Additionally, CFR is difficult to apply to multi-player games due
to the exponential growth of the game tree size. In this work, we introduce
PokerGPT, an end-to-end solver for playing Texas Hold'em with arbitrary number
of players and gaining high win rates, established on a lightweight large
language model (LLM). PokerGPT only requires simple textual information of
Poker games for generating decision-making advice, thus guaranteeing the
convenient interaction between AI and humans. We mainly transform a set of
textual records acquired from real games into prompts, and use them to
fine-tune a lightweight pre-trained LLM using reinforcement learning human
feedback technique. To improve fine-tuning performance, we conduct prompt
engineering on raw data, including filtering useful information, selecting
behaviors of players with high win rates, and further processing them into
textual instruction using multiple prompt engineering techniques. Through the
experiments, we demonstrate that PokerGPT outperforms previous approaches in
terms of win rate, model size, training time, and response speed, indicating
the great potential of LLMs in solving IIGs.