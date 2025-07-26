---
layout: publication
title: 'How To Train Your LLM Web Agent: A Statistical Diagnosis'
authors: "Dheeraj Vattikonda, Santhoshi Ravichandran, Emiliano Penaloza, Hadi Nekoei,\
  \ Megh Thakkar, Thibault Le Sellier de Chezelles, Nicolas Gontier, Miguel Mu\xF1\
  oz-m\xE1rmol, Sahar Omidi Shayegan, Stefania Raimondo, Xue Liu, Alexandre Drouin,\
  \ Laurent Charlin, Alexandre Pich\xE9, Alexandre Lacoste, Massimo Caccia"
conference: No Venue
year: 2025
bibkey: vattikonda2025how
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.04103'}]
tags: ["Training Techniques"]
short_authors: Vattikonda et al.
---
LLM-based web agents have recently made significant progress, but much of it has occurred in closed-source systems, widening the gap with open-source alternatives. Progress has been held back by two key challenges: first, a narrow focus on single-step tasks that overlooks the complexity of multi-step web interactions; and second, the high compute costs required to post-train LLM-based web agents. To address this, we present the first statistically grounded study on compute allocation for LLM web-agent post-training. Our approach uses a two-stage pipeline, training a Llama 3.1 8B student to imitate a Llama 3.3 70B teacher via supervised fine-tuning (SFT), followed by on-policy reinforcement learning. We find this process highly sensitive to hyperparameter choices, making exhaustive sweeps impractical. To spare others from expensive trial-and-error, we sample 1,370 configurations and use bootstrapping to estimate effective hyperparameters. Our results show that combining SFT with on-policy RL consistently outperforms either approach alone on both WorkArena and MiniWob++. Further, this strategy requires only 55% of the compute to match the peak performance of pure SFT on MiniWob++, effectively pushing the compute-performance Pareto frontier, and is the only strategy that can close the gap with closed-source models.

https://huggingface.co/discussions/paper/686dbfe2cb5725779c60b324