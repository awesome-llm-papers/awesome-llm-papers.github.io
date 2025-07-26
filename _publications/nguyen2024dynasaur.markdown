---
layout: publication
title: 'Dynasaur: Large Language Agents Beyond Predefined Actions'
authors: Dang Nguyen, Viet Dac Lai, Seunghyun Yoon, Ryan A. Rossi, Handong Zhao, Ruiyi
  Zhang, Puneet Mathur, Nedim Lipka, Yu Wang, Trung Bui, Franck Dernoncourt, Tianyi
  Zhou
conference: No Venue
year: 2024
bibkey: nguyen2024dynasaur
additional_links: [{name: Code, url: 'https://github.com/adobe-research/dynasaur\{https://github.com/adobe-research/dynasaur\'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6729bd842f893196814b31fa'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2411.01747'}]
tags: ["Agentic"]
short_authors: Nguyen et al.
---
Existing LLM agent systems typically select actions from a fixed and predefined set at every step. While this approach is effective in closed, narrowly-scoped environments, we argue that it presents two major challenges when deploying LLM agents in real-world scenarios: (1) selecting from a fixed set of actions significantly restricts the planning and acting capabilities of LLM agents, and (2) this approach requires substantial human effort to enumerate and implement all possible actions, which becomes impractical in complex environments with a vast number of potential actions. In this work, we propose an LLM agent framework that enables the dynamic creation and composition of actions in an online manner. In this framework, the agent interacts with the environment by generating and executing programs written in a general-purpose programming language at each step. Furthermore, generated actions are accumulated over time for future reuse. Our extensive experiments on the GAIA benchmark demonstrate that this framework offers significantly greater flexibility and outperforms previous methods. Notably, it allows an LLM agent to recover in scenarios where no relevant action exists in the predefined set or when existing actions fail due to unforeseen edge cases. At the time of writing, we hold the top position on the GAIA public leaderboard. Our code can be found in https://github.com/adobe-research/dynasaur\{https://github.com/adobe-research/dynasaur\}.

https://huggingface.co/discussions/paper/6729bd842f893196814b31fa