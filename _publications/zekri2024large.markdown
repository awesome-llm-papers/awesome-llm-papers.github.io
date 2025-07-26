---
layout: publication
title: Large Language Models As Markov Chains
authors: "Oussama Zekri, Ambroise Odonnat, Abdelhakim Benechehab, Linus Bleistein,\
  \ Nicolas Boull\xE9, Ievgen Redko"
conference: No Venue
year: 2024
bibkey: zekri2024large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.02724'}]
tags: ["Training Techniques"]
short_authors: Zekri et al.
---
Large language models (LLMs) have proven to be remarkably efficient, both across a wide range of natural language processing tasks and well beyond them. However, a comprehensive theoretical analysis of the origins of their impressive performance remains elusive. In this paper, we approach this challenging task by drawing an equivalence between generic autoregressive language models with vocabulary of size T and context window of size K and Markov chains defined on a finite state space of size O(T^K). We derive several surprising findings related to the existence of a stationary distribution of Markov chains that capture the inference power of LLMs, their speed of convergence to it, and the influence of the temperature on the latter. We then prove pre-training and in-context generalization bounds and show how the drawn equivalence allows us to enrich their interpretation. Finally, we illustrate our theoretical guarantees with experiments on several recent LLMs to highlight how they capture the behavior observed in practice.

https://huggingface.co/discussions/paper/66ffa1083187ada66f619fec