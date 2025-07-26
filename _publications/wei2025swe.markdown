---
layout: publication
title: 'SWE-RL: Advancing LLM Reasoning Via Reinforcement Learning On Open Software
  Evolution'
authors: Yuxiang Wei, Olivier Duchenne, Jade Copet, Quentin Carbonneaux, Lingming
  Zhang, Daniel Fried, Gabriel Synnaeve, Rishabh Singh, Sida I. Wang
conference: No Venue
year: 2025
bibkey: wei2025swe
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67be845b8a5a8054231457d6'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.18449'}]
tags: ["Has Code", "Llm For Code", "Reinforcement Learning", "Tools"]
short_authors: Wei et al.
---
The recent DeepSeek-R1 release has demonstrated the immense potential of reinforcement learning (RL) in enhancing the general reasoning capabilities of large language models (LLMs). While DeepSeek-R1 and other follow-up work primarily focus on applying RL to competitive coding and math problems, this paper introduces SWE-RL, the first approach to scale RL-based LLM reasoning for real-world software engineering. Leveraging a lightweight rule-based reward (e.g., the similarity score between ground-truth and LLM-generated solutions), SWE-RL enables LLMs to autonomously recover a developer's reasoning processes and solutions by learning from extensive open-source software evolution data -- the record of a software's entire lifecycle, including its code snapshots, code changes, and events such as issues and pull requests. Trained on top of Llama 3, our resulting reasoning model, Llama3-SWE-RL-70B, achieves a 41.0% solve rate on SWE-bench Verified -- a human-verified collection of real-world GitHub issues. To our knowledge, this is the best performance reported for medium-sized (<100B) LLMs to date, even comparable to leading proprietary LLMs like GPT-4o. Surprisingly, despite performing RL solely on software evolution data, Llama3-SWE-RL has even emerged with generalized reasoning skills. For example, it shows improved results on five out-of-domain tasks, namely, function coding, library use, code reasoning, mathematics, and general language understanding, whereas a supervised-finetuning baseline even leads to performance degradation on average. Overall, SWE-RL opens up a new direction to improve the reasoning capabilities of LLMs through reinforcement learning on massive software engineering data.

https://huggingface.co/discussions/paper/67be845b8a5a8054231457d6