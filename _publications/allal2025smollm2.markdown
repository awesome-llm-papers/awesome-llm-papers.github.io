---
layout: publication
title: 'Smollm2: When Smol Goes Big -- Data-centric Training Of A Small Language Model'
authors: "Loubna Ben Allal, Anton Lozhkov, Elie Bakouch, Gabriel Mart\xEDn Bl\xE1\
  zquez, Guilherme Penedo, Lewis Tunstall, Andr\xE9s Marafioti, Hynek Kydl\xED\u010D\
  ek, Agust\xEDn Piqueres Lajar\xEDn, Vaibhav Srivastav, Joshua Lochner, Caleb Fahlgren,\
  \ Xuan-son Nguyen, Cl\xE9mentine Fourrier, Ben Burtenshaw, Hugo Larcher, Haojun\
  \ Zhao, Cyril Zakka, Mathieu Morlon, Colin Raffel, Leandro von Werra, Thomas Wolf"
conference: No Venue
year: 2025
bibkey: allal2025smollm2
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67a446a9430e358f5d5ac4f8'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.02737'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Allal et al.
---
While large language models have facilitated breakthroughs in many applications of artificial intelligence, their inherent largeness makes them computationally expensive and challenging to deploy in resource-constrained settings. In this paper, we document the development of SmolLM2, a state-of-the-art "small" (1.7 billion parameter) language model (LM). To attain strong performance, we overtrain SmolLM2 on ~11 trillion tokens of data using a multi-stage training process that mixes web text with specialized math, code, and instruction-following data. We additionally introduce new specialized datasets (FineMath, Stack-Edu, and SmolTalk) at stages where we found existing datasets to be problematically small or low-quality. To inform our design decisions, we perform both small-scale ablations as well as a manual refinement process that updates the dataset mixing rates at each stage based on the performance at the previous stage. Ultimately, we demonstrate that SmolLM2 outperforms other recent small LMs including Qwen2.5-1.5B and Llama3.2-1B. To facilitate future research on LM development as well as applications of small LMs, we release both SmolLM2 as well as all of the datasets we prepared in the course of this project.

https://huggingface.co/discussions/paper/67a446a9430e358f5d5ac4f8