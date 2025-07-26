---
layout: publication
title: Self-rewarding Language Models
authors: Weizhe Yuan, Richard Yuanzhe Pang, Kyunghyun Cho, Sainbayar Sukhbaatar, Jing
  Xu, Jason Weston
conference: No Venue
year: 2024
bibkey: yuan2024self
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.10020'}]
tags: ["Model Architecture", "Reinforcement Learning"]
short_authors: Yuan et al.
---
We posit that to achieve superhuman agents, future models require superhuman feedback in order to provide an adequate training signal. Current approaches commonly train reward models from human preferences, which may then be bottlenecked by human performance level, and secondly these separate frozen reward models cannot then learn to improve during LLM training. In this work, we study Self-Rewarding Language Models, where the language model itself is used via LLM-as-a-Judge prompting to provide its own rewards during training. We show that during Iterative DPO training that not only does instruction following ability improve, but also the ability to provide high-quality rewards to itself. Fine-tuning Llama 2 70B on three iterations of our approach yields a model that outperforms many existing systems on the AlpacaEval 2.0 leaderboard, including Claude 2, Gemini Pro, and GPT-4 0613. While only a preliminary study, this work opens the door to the possibility of models that can continually improve in both axes.

https://huggingface.co/discussions/paper/65a9da1bf2878c013d172f5c