---
layout: publication
title: Can Large Language Models Explore In-context?
authors: Akshay Krishnamurthy, Keegan Harris, Dylan J. Foster, Cyril Zhang, Aleksandrs
  Slivkins
conference: No Venue
year: 2024
bibkey: krishnamurthy2024can
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.15371'}]
tags: ["Datasets", "Fine-Tuning", "Model Architecture", "Prompting", "Reinforcement Learning", "Training Techniques"]
short_authors: Krishnamurthy et al.
---
We investigate the extent to which contemporary Large Language Models (LLMs) can engage in exploration, a core capability in reinforcement learning and decision making. We focus on native performance of existing LLMs, without training interventions. We deploy LLMs as agents in simple multi-armed bandit environments, specifying the environment description and interaction history entirely in-context, i.e., within the LLM prompt. We experiment with GPT-3.5, GPT-4, and Llama2, using a variety of prompt designs, and find that the models do not robustly engage in exploration without substantial interventions: i) Across all of our experiments, only one configuration resulted in satisfactory exploratory behavior: GPT-4 with chain-of-thought reasoning and an externally summarized interaction history, presented as sufficient statistics; ii) All other configurations did not result in robust exploratory behavior, including those with chain-of-thought reasoning but unsummarized history. Although these findings can be interpreted positively, they suggest that external summarization -- which may not be possible in more complex settings -- is important for obtaining desirable behavior from LLM agents. We conclude that non-trivial algorithmic interventions, such as fine-tuning or dataset curation, may be required to empower LLM-based decision making agents in complex settings.

https://huggingface.co/discussions/paper/6600d47a8270811586f9fe6d