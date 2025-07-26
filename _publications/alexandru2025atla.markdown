---
layout: publication
title: 'Atla Selene Mini: A General Purpose Evaluation Model'
authors: Andrei Alexandru, Antonia Calvi, Henry Broomfield, Jackson Golden, Kyle Dai,
  Mathias Leys, Maurice Burger, Max Bartolo, Roman Engeler, Sashank Pisupati, Toby
  Drane, Young Sun Park
conference: No Venue
year: 2025
bibkey: alexandru2025atla
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.17195'}]
tags: ["Evaluation", "Tools"]
short_authors: Alexandru et al.
---
We introduce Atla Selene Mini, a state-of-the-art small language model-as-a-judge (SLMJ). Selene Mini is a general-purpose evaluator that outperforms the best SLMJs and GPT-4o-mini on overall performance across 11 out-of-distribution benchmarks, spanning absolute scoring, classification, and pairwise preference tasks. It is the highest-scoring 8B generative model on RewardBench, surpassing strong baselines like GPT-4o and specialized judges. To achieve this, we develop a principled data curation strategy that augments public datasets with synthetically generated critiques and ensures high quality through filtering and dataset ablations. We train our model on a combined direct preference optimization (DPO) and supervised fine-tuning (SFT) loss, and produce a highly promptable evaluator that excels in real-world scenarios. Selene Mini shows dramatically improved zero-shot agreement with human expert evaluations on financial and medical industry datasets. It is also robust to variations in prompt format. Preliminary results indicate that Selene Mini is the top-ranking evaluator in a live, community-driven Judge Arena. We release the model weights on HuggingFace (https://hf.co/AtlaAI/Selene-1-Mini-Llama-3.1-8B) and Ollama to encourage widespread community adoption.

https://huggingface.co/discussions/paper/679ae76b5c55250b484838e0