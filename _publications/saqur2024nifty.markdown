---
layout: publication
title: NIFTY Financial News Headlines Dataset
authors: Saqur et al.
conference: AI Open
year: 2024
bibkey: saqur2024nifty
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.09747'}]
tags: [Training Techniques, Prompting, Agentic, Tools, Time Series, Reinforcement
    Learning, Applications, Fine Tuning, Datasets]
---
We introduce and make publicly available the NIFTY Financial News Headlines
dataset, designed to facilitate and advance research in financial market
forecasting using large language models (LLMs). This dataset comprises two
distinct versions tailored for different modeling approaches: (i) NIFTY-LM,
which targets supervised fine-tuning (SFT) of LLMs with an auto-regressive,
causal language-modeling objective, and (ii) NIFTY-RL, formatted specifically
for alignment methods (like reinforcement learning from human feedback (RLHF))
to align LLMs via rejection sampling and reward modeling. Each dataset version
provides curated, high-quality data incorporating comprehensive metadata,
market indices, and deduplicated financial news headlines systematically
filtered and ranked to suit modern LLM frameworks. We also include experiments
demonstrating some applications of the dataset in tasks like stock price
movement and the role of LLM embeddings in information acquisition/richness.
The NIFTY dataset along with utilities (like truncating prompt's context length
systematically) are available on Hugging Face at
https://huggingface.co/datasets/raeidsaqur/NIFTY.