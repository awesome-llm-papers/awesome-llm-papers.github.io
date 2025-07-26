---
layout: publication
title: 'The Common Pile V0.1: An 8TB Dataset Of Public Domain And Openly Licensed
  Text'
authors: Nikhil Kandpal, Brian Lester, Colin Raffel, Sebastian Majstorovic, Stella
  Biderman, Baber Abbasi, Luca Soldaini, Enrico Shippole, A. Feder Cooper, Aviya Skowron,
  John Kirchenbauer, Shayne Longpre, Lintang Sutawika, Alon Albalak, Zhenlin Xu, Guilherme
  Penedo, Loubna Ben Allal, Elie Bakouch, John David Pressman, Honglu Fan, Dashiell
  Stander, Guangyu Song, Aaron Gokaslan, Tom Goldstein, Brian R. Bartoldson, Bhavya
  Kailkhura, Tyler Murray
conference: No Venue
year: 2025
bibkey: kandpal2025common
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/684247f85d537e0e5ecb73d3'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.05209'}]
tags: ["Datasets"]
short_authors: Kandpal et al.
---
Large language models (LLMs) are typically trained on enormous quantities of unlicensed text, a practice that has led to scrutiny due to possible intellectual property infringement and ethical concerns. Training LLMs on openly licensed text presents a first step towards addressing these issues, but prior data collection efforts have yielded datasets too small or low-quality to produce performant LLMs. To address this gap, we collect, curate, and release the Common Pile v0.1, an eight terabyte collection of openly licensed text designed for LLM pretraining. The Common Pile comprises content from 30 sources that span diverse domains including research papers, code, books, encyclopedias, educational materials, audio transcripts, and more. Crucially, we validate our efforts by training two 7 billion parameter LLMs on text from the Common Pile: Comma v0.1-1T and Comma v0.1-2T, trained on 1 and 2 trillion tokens respectively. Both models attain competitive performance to LLMs trained on unlicensed text with similar computational budgets, such as Llama 1 and 2 7B. In addition to releasing the Common Pile v0.1 itself, we also release the code used in its creation as well as the training mixture and checkpoints for the Comma v0.1 models.

https://huggingface.co/discussions/paper/684247f85d537e0e5ecb73d3