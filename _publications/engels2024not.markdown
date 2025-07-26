---
layout: publication
title: Not All Language Model Features Are Linear
authors: Joshua Engels, Isaac Liao, Eric J. Michaud, Wes Gurnee, Max Tegmark
conference: No Venue
year: 2024
bibkey: engels2024not
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66501b5cd62f7e57e34d7b20'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2405.14860'}]
tags: ["Model Architecture"]
short_authors: Engels et al.
---
Recent work has proposed the linear representation hypothesis: that language models perform computation by manipulating one-dimensional representations of concepts ("features") in activation space. In contrast, we explore whether some language model representations may be inherently multi-dimensional. We begin by developing a rigorous definition of irreducible multi-dimensional features based on whether they can be decomposed into either independent or non-co-occurring lower-dimensional features. Motivated by these definitions, we design a scalable method that uses sparse autoencoders to automatically find multi-dimensional features in GPT-2 and Mistral 7B. These auto-discovered features include strikingly interpretable examples, e.g. circular features representing days of the week and months of the year. We identify tasks where these exact circles are used to solve computational problems involving modular arithmetic in days of the week and months of the year. Finally, we provide evidence that these circular features are indeed the fundamental unit of computation in these tasks with intervention experiments on Mistral 7B and Llama 3 8B, and we find further circular representations by breaking down the hidden states for these tasks into interpretable components.

https://huggingface.co/discussions/paper/66501b5cd62f7e57e34d7b20