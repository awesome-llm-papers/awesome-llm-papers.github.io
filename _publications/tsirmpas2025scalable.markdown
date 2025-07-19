---
layout: publication
title: Scalable Evaluation Of Online Facilitation Strategies Via Synthetic Simulation
  Of Discussions
authors: Tsirmpas Dimitris, Androutsopoulos Ion, Pavlopoulos John
conference: Distance Education
year: 2025
bibkey: tsirmpas2025scalable
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.16505'}]
tags: [Tools, Evaluation, Datasets]
---
Limited large-scale evaluations exist for facilitation strategies of online discussions due to significant costs associated with human involvement. An effective solution is synthetic discussion simulations using Large Language Models (LLMs) to create initial pilot experiments. We propose a simple, generalizable, LLM-driven methodology to prototype the development of LLM facilitators, and produce high-quality synthetic data without human involvement. We use our methodology to test whether current facilitation strategies can improve the performance of LLM facilitators. We find that, while LLM facilitators significantly improve synthetic discussions, there is no evidence that the application of more elaborate facilitation strategies proposed in modern Social Science research lead to further improvements in discussion quality, compared to more basic approaches. Additionally, we find that small LLMs (such as Mistral Nemo 12B) can perform comparably to larger models (such as LLaMa 70B), and that special instructions must be used for instruction-tuned models to induce toxicity in synthetic discussions. We confirm that each component of our methodology contributes substantially to high quality data via an ablation study. We release an open-source framework, "SynDisco" (pip install syndisco), which implements our methodology. We also release the "Virtual Moderation Dataset" (https://paperswithcode.com/dataset/vmd), a large, publicly available dataset containing LLM-generated and LLM-annotated discussions using multiple open-source LLMs.