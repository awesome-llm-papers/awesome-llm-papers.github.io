---
layout: publication
title: 'Fingpt: Democratizing Internet-scale Data For Financial Large Language Models'
authors: Liu et al.
conference: SSRN Electronic Journal
year: 2023
bibkey: liu2023fingpt
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.10485'}]
tags: [Training Techniques, GPT, Agentic, Tools, Transformer, Model Architecture,
  Reinforcement Learning, Applications, Fine Tuning, Datasets]
---
Large language models (LLMs) have demonstrated remarkable proficiency in
understanding and generating human-like texts, which may potentially
revolutionize the finance industry. However, existing LLMs often fall short in
the financial field, which is mainly attributed to the disparities between
general text data and financial text data. Unfortunately, there is only a
limited number of financial text datasets available, and BloombergGPT, the
first financial LLM (FinLLM), is close-sourced (only the training logs were
released). In light of this, we aim to democratize Internet-scale financial
data for LLMs, which is an open challenge due to diverse data sources, low
signal-to-noise ratio, and high time-validity. To address the challenges, we
introduce an open-sourced and data-centric framework, Financial Generative
Pre-trained Transformer (FinGPT), that automates the collection and curation of
real-time financial data from 34 diverse sources on the Internet, providing
researchers and practitioners with accessible and transparent resources to
develop their FinLLMs. Additionally, we propose a simple yet effective strategy
for fine-tuning FinLLM using the inherent feedback from the market, dubbed
Reinforcement Learning with Stock Prices (RLSP). We also adopt the Low-rank
Adaptation (LoRA, QLoRA) method that enables users to customize their own
FinLLMs from general-purpose LLMs at a low cost. Finally, we showcase several
FinGPT applications, including robo-advisor, sentiment analysis for algorithmic
trading, and low-code development. FinGPT aims to democratize FinLLMs,
stimulate innovation, and unlock new opportunities in open finance. The codes
have been open-sourced.