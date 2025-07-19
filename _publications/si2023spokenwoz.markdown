---
layout: publication
title: 'Spokenwoz: A Large-scale Speech-text Benchmark For Spoken Task-oriented Dialogue
  Agents'
authors: Si et al.
conference: Computational Intelligence
year: 2023
bibkey: si2023spokenwoz
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.13040'}]
tags: [GPT, Agentic, Evaluation, Model Architecture, Reinforcement Learning, Security,
  Datasets]
---
Task-oriented dialogue (TOD) models have made significant progress in recent years. However, previous studies primarily focus on datasets written by annotators, which has resulted in a gap between academic research and real-world spoken conversation scenarios. While several small-scale spoken TOD datasets are proposed to address robustness issues such as ASR errors, they ignore the unique challenges in spoken conversation. To tackle the limitations, we introduce SpokenWOZ, a large-scale speech-text dataset for spoken TOD, containing 8 domains, 203k turns, 5.7k dialogues and 249 hours of audios from human-to-human spoken conversations. SpokenWOZ further incorporates common spoken characteristics such as word-by-word processing and reasoning in spoken language. Based on these characteristics, we present cross-turn slot and reasoning slot detection as new challenges. We conduct experiments on various baselines, including text-modal models, newly proposed dual-modal models, and LLMs, e.g., ChatGPT. The results show that the current models still have substantial room for improvement in spoken conversation, where the most advanced dialogue state tracker only achieves 25.65% in joint goal accuracy and the SOTA end-to-end model only correctly completes the user request in 52.1% of dialogues. The dataset, code, and leaderboard are available: https://spokenwoz.github.io/.