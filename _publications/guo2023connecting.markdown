---
layout: publication
title: Connecting Large Language Models With Evolutionary Algorithms Yields Powerful
  Prompt Optimizers
authors: Qingyan Guo, Rui Wang, Junliang Guo, Bei Li, Kaitao Song, Xu Tan, Guoqing
  Liu, Jiang Bian, Yujiu Yang
conference: No Venue
year: 2023
bibkey: guo2023connecting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.08532'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Guo et al.
---
Large Language Models (LLMs) excel in various tasks, but they rely on carefully crafted prompts that often demand substantial human effort. To automate this process, in this paper, we propose a novel framework for discrete prompt optimization, called EvoPrompt, which borrows the idea of evolutionary algorithms (EAs) as they exhibit good performance and fast convergence. To enable EAs to work on discrete prompts, which are natural language expressions that need to be coherent and human-readable, we connect LLMs with EAs. This approach allows us to simultaneously leverage the powerful language processing capabilities of LLMs and the efficient optimization performance of EAs. Specifically, abstaining from any gradients or parameters, EvoPrompt starts from a population of prompts and iteratively generates new prompts with LLMs based on the evolutionary operators, improving the population based on the development set. We optimize prompts for both closed- and open-source LLMs including GPT-3.5 and Alpaca, on 9 datasets spanning language understanding and generation tasks. EvoPrompt significantly outperforms human-engineered prompts and existing methods for automatic prompt generation by up to 25% and 14% respectively. Furthermore, EvoPrompt demonstrates that connecting LLMs with EAs creates synergies, which could inspire further research on the combination of LLMs and conventional algorithms.

https://huggingface.co/discussions/paper/6507a909557a87f111e64067